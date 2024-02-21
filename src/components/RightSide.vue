<template>
    <div class="right-side">
        <div class="top">
            <div class="theme-toggler" @click="toggleTheme">
                <span
                    class="material-icons-sharp light"
                    :class="{ light: !darkTheme, active: !darkTheme }"
                    >light_mode</span
                >
                <span
                    class="material-icons-sharp dark"
                    :class="{ dark: darkTheme, active: darkTheme }"
                    >dark_mode</span
                >
            </div>
            <div class="profile">
                <h3 class="text-muted">Admin</h3>
                <span class="material-icons-sharp"> person </span>
            </div>
        </div>

        <div class="recent-updates">
            <h2>Recent Update</h2>
            <div class="updates">
                <div class="update">
                    <div class="profile-photo">
                        <img src="" alt="" />
                    </div>
                    <div class="message">
                        <p><b>Mike Tyson</b> Something text</p>
                        <small class="text-muted">2 Minutes Ago</small>
                    </div>
                </div>
                <div class="update">
                    <div class="profile-photo">
                        <img src="" alt="" />
                    </div>
                    <div class="message">
                        <p><b>Mike Tyson</b> Something text</p>
                        <small class="text-muted">2 Minutes Ago</small>
                    </div>
                </div>
                <div class="update">
                    <div class="profile-photo">
                        <img src="" alt="" />
                    </div>
                    <div class="message">
                        <p><b>Mike Tyson</b> Something text</p>
                        <small class="text-muted">2 Minutes Ago</small>
                    </div>
                </div>
            </div>
        </div>

        <div class="sales-analytics">
            <h2>Sales Analytics</h2>
            <div class="item online">
                <div class="icon">
                    <span class="material-icons-sharp"> shopping_cart </span>
                </div>
                <div class="discr">
                    <div class="info">
                        <h3>ONLINE ORDERS</h3>
                        <small class="text-muted">Last 24 Hours </small>
                    </div>
                    <h5 class="success">+39%</h5>
                    <h3>7898</h3>
                </div>
            </div>
            <div class="item offline">
                <div class="icon">
                    <span class="material-icons-sharp"> local_mall </span>
                </div>
                <div class="discr">
                    <div class="info">
                        <h3>OFLINE ORDERS</h3>
                        <small class="text-muted">Last 24 Hours </small>
                    </div>
                    <h5 class="danger">-23%</h5>
                    <h3>5294</h3>
                </div>
            </div>
            <div class="item customers">
                <div class="icon">
                    <span class="material-icons-sharp"> person </span>
                </div>
                <div class="discr">
                    <div class="info">
                        <h3>NEW CUSTOMERS</h3>
                        <small class="text-muted">Last 24 Hours </small>
                    </div>
                    <h5 class="success">+25%</h5>
                    <h3>2085</h3>
                </div>
            </div>
            <div class="item add-product">
                <div>
                    <span class="material-icons-sharp"> add </span>
                    <h3>Add Product</h3>
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
import { ref } from "vue";
const darkTheme = ref(false);

const toggleTheme = () => {
    darkTheme.value = !darkTheme.value;
    if (darkTheme.value) {
        document.body.classList.add("dark-theme-variables");
    } else {
        document.body.classList.remove("dark-theme-variables");
    }
};
</script>
