<template>
    <div>
        <div>회원 가입 페이지</div>
        <SignupForm></SignupForm>
    </div>
</template>

<script>
    import SignupForm from "@/components/SignupForm";

    export default {
        name: "SignupPage",
        components: {SignupForm},
        created() {
            console.log(document.location.href)
        }
    };
</script>

<style scoped></style>
