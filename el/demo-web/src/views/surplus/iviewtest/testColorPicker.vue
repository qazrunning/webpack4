<template>
<div>
    <Row>
        <Col span="12">
            有默认值
            <ColorPicker v-model="color1" />
        </Col>
        <Col span="12">
            无默认值
            <ColorPicker v-model="color2" />
        </Col>
    </Row>
    <br><br>
     <ColorPicker v-model="color3" alpha />
    </div>
</template>
<script>
    export default {
        data () {
            return {
                color1: '#19be6b',
                color2: '',
                color3: 'rgba(25, 190,107, .5)'
            }
        }
    }
</script>