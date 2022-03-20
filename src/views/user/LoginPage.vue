<template>
        <div class="d-flex justify-center">
            <form @submit.prevent="onSubmit">
                <div>
                    아이디
                    <input type="text" v-model="writer"/>
                </div>
                <div>
                    비밀번호
                    <input type="text" v-model="writer"/>
                </div>
                <div>
                    이름
                    <input type="text" v-model="title"/>
                </div>
                <div align="start">
                    <div><v-btn color="blue" class="white--text" type="submit">로그인</v-btn></div>
                    <button class="blue--text" type="button">비밀번호 찾기</button>
                    <div>
                        <router-link style="text-decoration: none;" :to="{name: 'RegisterPage'}">
                        <v-btn color="blue" class="white--text">회원가입</v-btn>
                        </router-link>
                    </div>
                </div>
            </form>
        </div>

</template>

<script>
export default {
    setup() {
        
    },
}
</script>