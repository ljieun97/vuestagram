<template>
    <div class="mx-auto" style="width: 935px; height: 736px;">
        <v-card class="mx-auto"
                width="350"
                height="382"
                outlined>
            <form @submit.prevent="onSubmit">
                <br/>
                <h1 class="d-flex justify-center">Vuestagram</h1>
                <br/>
                <div class="d-flex justify-center">
                    <input style="border: 1px solid gray" type="text" placeholder="아이디" v-model="writer"/>
                </div>
                <div class="d-flex justify-center">
                    <input style="border: 1px solid gray" type="text" placeholder="비밀번호" v-model="writer"/>
                </div>
                <br/>
                <div class="d-flex justify-center"><v-btn color="blue" class="white--text" type="submit">로그인</v-btn></div>
            </form>
            <br/>
            <div class="d-flex justify-center">또는</div>
            <br/>
            <div class="d-flex justify-center"><button class="indigo--text" type="button">비밀번호를 잊으셨나요?</button></div>
        </v-card>
        <br/>
        <v-card class="mx-auto"
                width="350"
                height="63"
                outlined>
            <div align="center">
                계정이 없으신가요?
                <router-link style="text-decoration: none;" :to="{name: 'RegisterPage'}">
                <button class="blue--text" type="button">&nbsp;가입하기</button>
                </router-link>
            </div>
        </v-card>
    </div>        
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style>

.v-main {
    background-color: #f5f5f5;

}

</style>
