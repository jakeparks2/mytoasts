<script>
export default {
    props: ['message', 'type'],

    mounted() {
        this.$toasts.push({
            message: this.message,
            type: this.type,
            position: 'top-right',
        });
    },
};
</script>
