<template>
    <div>
        <div>
            <v-img src="@/assets/logo.png"/>
            <h1>아이디</h1>
            <button type="button">프로필 사진 바꾸기</button>
        </div>
        <form @submit.prevent="onSubmit">
            <table>
                <tr>
                    <td>이름</td>
                    <td>
                        <input type="text" v-model="title"/>
                        <div>사람들이 이름, 별명 또는 비즈니스 이름 등 회원님의 알려진 이름을 사용하여 회원님의 계정을 찾을 수 있도록 도와주세요.</div>
                    </td>
                </tr>
                <tr>
                    <td>소개</td>
                    <td>
                        <textarea cols="50" rows="20" v-model="content">
                        </textarea>
                    </td>
                </tr>
                <tr>
                    <td>아이디</td>
                    <td>
                        <input type="text" v-model="writer"/>
                    </td>
                </tr>
                <tr>
                    <td>비밀번호</td>
                    <td>
                        <input type="text" v-model="writer"/>
                    </td>
                </tr>            
            </table>

            <div>
                <button type="submit">제출</button>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    name: 'AccountsEditPage',
    data() {
        return {

        }
        
    },

}
</script>