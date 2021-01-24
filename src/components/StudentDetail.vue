<template>
    <div class="Student-Detali">
        <h1>{{ Student.title }}</h1>
        <br />
        <div style="padding: 0px 0px 0px 3px; font-size: 40px">
            
        </div>
        <br />
        <div>
            <img
            style="float: left; padding: 20px"
            width="250px"
            v-bind:src="Student.picture"
            />
        </div>
        <div style="padding: 0px 0px 10px 400px">
        <b>NAME:</b> {{ Student.studentName }} <br />
        <br /><b>StudentId:614234010</b> {{ Student.StudentId }} <br/>
        <br /><b>FirstName:</b> {{ Student.FirstName }} <br/>
        <br /><b>LastName:</b> {{ Student.LastName }} <br/>
        <br /><b>Weight:</b> {{ Student.weight }} <br/>
        <br /><b>Height:</b> {{ Student.height }} <br/>
        <br />
        <br />
        </div>
    </div>
</template>

<script>
export default {
    name: "StudentDetail",
    components:{},
    props: ["Student"],
};
</script>

<style>
.Student-Detail {
    background: rgb(fff,fff,fff);
    padding: 20px 30px 0px 400px;
    border-bottom-color: rgba(231, 247, 19, 0.938) 1px;
}
</style>