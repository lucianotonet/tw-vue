<template>
    <div class="bg-blue-gray-50">
        <h3 class="text-lg font-bold mb-2">
            Cards
        </h3>

        <TWCard class="hover:shadow-lg transform transition-all ease-in-out hover:-translate-y-px">
            This is a card
        </TWCard>
        <br><br><br>

        <TWCard no-body>
            This is a card
        </TWCard>

        <TWCard variant="naked">
            This is a card
        </TWCard>

        <TWCard variant="primary">
            This is a card
        </TWCard>

        <TWCard variant="secondary">
            This is a card
        </TWCard>

        <TWCard variant="success">
            This is a card
        </TWCard>

        <TWCard variant="danger">
            This is a card
        </TWCard>

        <TWCard variant="warning">
            This is a card
        </TWCard>

        <TWCard variant="info">
            This is a card
        </TWCard>

        <TWCard variant="light">
            This is a card
        </TWCard>

        <TWCard variant="dark">
            This is a card
        </TWCard>
    </div>
</template>

<script>
    import TWCard from '@/components/card/TWCard';

    export default {
        name: 'Cards',

        components: {
            TWCard,
        },

        data() {
            return {
            };
        },

        methods: {},
    };
</script>
