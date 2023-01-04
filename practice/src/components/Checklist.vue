<h1>Multiple Checkboxes</h1>
<div>
    <input v-model = "checkBoxes" value = "first" class = "form-check-input" type = "checkbox" id = "cb1">
    <label for = "cb1">First</label>
</div>
<div>
    <input v-model = "checkBoxes" value = "second" class = "form-check-input" type = "checkbox" id = "cb2">
    <label for = "cb2">Second</label>
</div>
<div>
    <input v-model = "checkBoxes" value = "third" class = "form-check-input" type = "checkbox" id = "cb3">
    <label for = "cb3">Third</label>
</div>

<script>
    Vue.createApp({
        data(){
            return{
                checkBoxes:[]
            }
        }
    }).mount('#app')
</script>