<template>
    <div>
        <section class="section">
            <div class="container-fliud">
                <img alt="Vue logo" class="rounded-circle" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Woman_1.jpg/220px-Woman_1.jpg">
                <h1>Software Developer</h1>
                <p>This is a fun project I built while learning vue.js and bootstrap</p>
                <button type="button" class="btn btn-primary btn-lg">Contact</button>
            </div>
        </section>

        <section class="protfolio">
            <h1>Portfolio</h1>
            <div class="container">
                <div class="row">
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="Vue logo" class="rounded-circle" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Woman_1.jpg/220px-Woman_1.jpg">
                                <h2>web project</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod. 
                                    Nullam id dolor id nibh ultricies vehicula ut id elit. 
                                    Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.
                                </p>
                                <button type="button" class="btn btn-outline-secondary">More</button>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                hello world
                            </div>
                        </div>
                    </div>   
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                hello world
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
    </div>
</template>

<style lang="css" scoped>
    .section{
        padding-top: 10%;
        padding-bottom: 10%;
    }

    .protfolio{
        background-color: #34345238;
        /* padding-top: 15%; */
        /* padding-bottom: 15%; */
        padding:15%
    }
</style>