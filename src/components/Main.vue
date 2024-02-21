<template>
    <main>
        <h1>Dashboard</h1>

        <div class="date">
            <input type="date" />
        </div>
        <div class="insights">
            <div class="sales">
                <span class="material-icons-sharp"> analytics </span>
                <div class="wrap">
                    <div class="content">
                        <div class="title">
                            <h3>Total sale</h3>
                            <h1>25,000</h1>
                        </div>
                        <div class="progress">
                            <svg>
                                <circle cx="38" cy="38" r="36"></circle>
                            </svg>
                            <div class="number">
                                <p>81%</p>
                            </div>
                        </div>
                    </div>
                </div>
                <small class="text-muted">Last 24 Hours</small>
            </div>

            <div class="expenses">
                <span class="material-icons-sharp"> bar_chart </span>
                <div class="wrap">
                    <div class="content">
                        <div class="title">
                            <h3>Total Expenses</h3>
                            <h1>25,000</h1>
                        </div>
                        <div class="progress">
                            <svg>
                                <circle cx="38" cy="38" r="36"></circle>
                            </svg>
                            <div class="number">
                                <p>62%</p>
                            </div>
                        </div>
                    </div>
                </div>
                <small class="text-muted">Last 24 Hours</small>
            </div>
            <div class="income">
                <span class="material-icons-sharp"> stacked_line_chart </span>
                <div class="wrap">
                    <div class="content">
                        <div class="title">
                            <h3>Total Income</h3>
                            <h1>25,000</h1>
                        </div>
                        <div class="progress">
                            <svg>
                                <circle cx="38" cy="38" r="36"></circle>
                            </svg>
                            <div class="number">
                                <p>44%</p>
                            </div>
                        </div>
                    </div>
                </div>
                <small class="text-muted">Last 24 Hours</small>
            </div>
        </div>

        <div class="recent-orders">
            <h2>Recent-Orders</h2>
            <table>
                <thead>
                    <tr>
                        <th>Product Name</th>
                        <th>Product Number</th>
                        <th>Payment</th>
                        <th>Status</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Foldable Mini Drone</td>
                        <td>85631</td>
                        <td>Due</td>
                        <td class="warning">Pending</td>
                        <td class="primary">Details</td>
                    </tr>
                    <tr>
                        <td>Foldable Mini Drone</td>
                        <td>85631</td>
                        <td>Due</td>
                        <td class="warning">Pending</td>
                        <td class="primary">Details</td>
                    </tr>
                    <tr>
                        <td>Foldable Mini Drone</td>
                        <td>85631</td>
                        <td>Due</td>
                        <td class="warning">Pending</td>
                        <td class="primary">Details</td>
                    </tr>
                    <tr>
                        <td>Foldable Mini Drone</td>
                        <td>85631</td>
                        <td>Due</td>
                        <td class="warning">Pending</td>
                        <td class="primary">Details</td>
                    </tr>
                    <tr>
                        <td>Foldable Mini Drone</td>
                        <td>85631</td>
                        <td>Due</td>
                        <td class="warning">Pending</td>
                        <td class="primary">Details</td>
                    </tr>
                </tbody>
            </table>
            <a href="#">Show All</a>
        </div>
    </main>
</template>
