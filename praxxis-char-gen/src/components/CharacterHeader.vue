<template>
    <div>
        <div class="grey-header-box">
            <div></div>
            <div class="smooth-white-box">
                <div class="character-title">Character Name</div>
                <div class="attribute-group">
                    <div>
                        <span class="attribute-key">Age: </span>
                        <span class="attribute-value">100 S. Cycles</span>
                    </div>
                    <div>
                        <span class="attribute-key">Gender: </span>
                        <span class="attribute-value">Nonbinary</span>
                    </div>
                    <div>
                        <span class="attribute-key">Species: </span>
                        <span class="attribute-value">Human</span>
                    </div>
                </div>
            </div>
            <div class="smooth-white-box">
                <div class="attribute-group">
                    <div class="attribute-key">Archetype 1:</div>
                    <div class="attribute-value">None</div>
                </div>
                <div class="attribute-group">
                    <div class="attribute-key">Archetype 2:</div>
                    <div class="attribute-value">None</div>
                </div>
            </div>
            <div class="smooth-white-box">
                <div class="attribute-group">
                    <div>
                        <span class="attribute-key">Power: </span>
                        <span class="attribute-value">100 / 100</span>
                    </div>
                    <div>
                        <span class="attribute-key">Xeno: </span>
                        <span class="attribute-value">100 / 100</span>
                    </div>
                    <div>
                        <span class="attribute-key">Credits: </span>
                        <span class="attribute-value">100</span>
                    </div>
                </div>
            </div>
            <div>
                <div class="page-list">
                    <ul>
                        <li>Overview</li>
                        <li>Items</li>
                        <li>Skills and Attributes</li>
                        <li>Description</li>
                        <li>Home</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Character Header",
};
</script>

<style scoped>
.attribute-key {
    font-weight: bold;
}
.attribute-group {
    font-size: 16px;
    padding-left: 20px;
    padding-top: 10px;
    text-align: left;
}
.attribute-value {
    font-style: italic;
    padding-right: 2px;
}
.character-title {
    font-size: 21px;
    font-weight: bold;
    text-align: center;
    text-decoration: underline;
}
.grey-header-box {
    background-color: #dbdbdb;
    border: 1px solid black;
    display: grid;
    grid: auto / 20% 20% 16% 16% auto;
    min-height: 100px;
}
.page-list {
    font-size: 18px;
    min-height: 100px;
    padding-right: 20px;
    text-align: left;
}
.smooth-white-box {
    background-color: white;
    border: 1px solid black;
    border-radius: 15px;
    margin: 10px;
    min-height: 100px;
}
</style>
