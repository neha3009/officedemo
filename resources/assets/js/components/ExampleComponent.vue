<template>
    <div class="container">
        <h1> Box Builder</h1>
        <div class="tab-navigation">
            <ul>
                <li data-id="0">
                    <span class="round"></span>
                    <p>STEP 1</p>
                    <p>Choose your box color</p>
                </li>
                <li data-id="1">
                    <span class="round"></span>
                    <p>STEP 2</p>
                    <p>Choose your Items</p>
                </li>
                <li data-id="2">
                    <span class="round"></span>
                    <p>STEP 3</p>
                    <p>Select Your Card</p>
                </li>
                <li data-id="3">
                    <span class="round"></span>
                    <p>STEP 4</p>
                    <p>Place your Order</p>
                </li>
            </ul>
        </div>
        <div class="tab-content">
            <div id="panel0" class="panels">
                <div class="box-step-details">
                    <h2>Step 1 of 3</h2>
                    <p>Choose your box color</p>
                </div>
                <div class="box-full-panel">
                    <a href="javascript:void(0)" id="white-box">
                      <div class="box-panel white">
                        <div class="inner-box">
                            <div class="inner-box___again">
                                <p>White Box</p>
                            </div>
                        </div>
                      </div>
                    </a>
                    <a href="javascript:void(0)" id="black-box">
                        <div class="box-panel black">
                            <div class="inner-box">
                                <div class="inner-box___again">
                                    <p>Black Box</p>
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    // export default {
    //     mounted() {
    //         console.log('Component mounted.')
    //     }
    // }
    module.exports = {
        data() {
            return {
                selectedOs: "blackbox"
            }
        },
        methods: {

        }
    }

</script>
<style scoped>
    .selected { border: 1px solid red; }
</style>
