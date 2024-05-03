<script setup>
    const error = useError();

    const handelError = () => {
       clearError({
            redirect: "/",
       });
    };
</script> 
