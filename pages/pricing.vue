<template>
    <div>
        <section class="section-pricing-top">
            <div class="head">
                <h1>Pick a plan. Grow faster <br> with Foundation</h1>
                <p>Try for free for 14 days.</p>
            </div>
            <div class="content">
                <div class="items">
                    <div class="columns">
                        <div class="column">
                            <div class="card">
                                <div class="card-nav">
                                    <b>Save 30%</b> <small>this plan</small>
                                </div>
                                <div class="card-head">
                                    <img src="~assets/image/software-dev.png">
                                    <h3>Standart</h3>
                                    <p>Works perfect for small teams and companies</p>
                                    <span>$89</span> <small>/mo</small>
                                    <button class="plan-try">Try for Free</button>
                                </div>
                                <div class="card-body">
                                    <ul>
                                        <li>Upload up to <b>200 MB</b></li>
                                        <li>View message performance and test against variants</li>
                                        <li>Control groups to improve results</li>
                                        <li>Engage customers</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <div class="column">
                            <div class="card">
                                <div class="card-nav">
                                    <b>Save 30%</b> <small>this plan</small>
                                </div>
                                <div class="card-head">
                                    <img src="~assets/image/profesional.png">
                                    <h3>Professional</h3>
                                    <p>Works perfect for small teams and companies</p>
                                    <span>$249</span> <small>/mo</small>
                                    <button class="plan-try">Try for Free</button>
                                </div>
                                <div class="card-body">
                                    <ul>
                                        <li>Upload up to <b>1000 MB</b></li>
                                        <li>View message performance and test against variants</li>
                                        <li>Control groups to improve results</li>
                                        <li>Engage customers</li>
                                        <li>Unlimited subscriptions</li>
                                        <li>Free Support</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <div class="column">
                            <div class="card">
                                <div class="card-nav">
                                    <b>Save 30%</b> <small>this plan</small>
                                </div>
                                <div class="card-head">
                                    <img src="~assets/image/email-marketing.png">
                                    <h3>Corporate</h3>
                                    <p>Works perfect for small teams and companies</p>
                                    <span>$899</span> <small>/mo</small>
                                    <button class="plan-try">Try for Free</button>
                                </div>
                                <div class="card-body">
                                    <ul>
                                        <li>Upload up to <b>5000 MB</b></li>
                                        <li>View message performance and test against variants</li>
                                        <li>Control groups to improve results</li>
                                        <li>Engage customers</li>
                                        <li>Unlimited subscriptions</li>
                                        <li>Unlimited messages</li>
                                        <li>Free Support</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section-pricing-question">
            <div class="head">
                <h1>Your questions, answered</h1>
            </div>
            <div class="faq">
                <div class="columns">
                    <div class="column">
                        <h3>Can I cancel anytime?</h3>
                        <p>Of course. Contact our Client <b>Support team</b> prior to your next billing cycle and we'll take care of your request.</p>
                    </div>
                    <div class="column">
                        <h3>My team has credits. How do we use them?</h3>
                        <p>Once your team signs up for a subscription plan, we’ll draw against your credit balance until it runs out. Only then will we start charging your subscription to your credit card.</p>
                    </div>
                </div>
                <div class="columns">
                    <div class="column">
                        <h3>Is there a setup fee?</h3>
                        <p>We’ll make a one-time, prorated charge to your credit card to cover your new team member’s account for the remainder of the current billing period.</p>
                    </div>
                    <div class="column">
                        <h3>Can I cancel anytime?</h3>
                        <p>Of course. Contact our Client Support team prior to your next billing cycle and we'll take care of your request.</p>
                    </div>
                </div>
                <div class="columns">
                    <div class="column">
                        <h3>What are my payment options - credit card and/or invoicing?</h3>
                        <p>You can use your credit card to pay for any plan. If you sign up for an Annual subscription and plan to spend at least $2,000.</p>
                    </div>
                    <div class="column">
                        <h3>Can we get a refund?</h3>
                        <p>Team Owners can change the team’s subscription level. There are two options when downgrading from a paid plan to the Free plan.</p>
                    </div>
                </div>
            </div>    
        </section>
        <section class="section-home-nine">
            <div class="columns">
                <div class="column left-content">
                <img src="~assets/image/dog.png">
                </div>
                <div class="column is-three-fifths right-content">
                <div class="content">
                    <h1>Start your free trial.</h1>
                    <p>Get notified about company updates, news and blog posts. We hate spam.</p>
                    <div class="form">
                    <form class="">
                        <input type="text" placeholder="Enter your email">
                        <button class="btn primary get-started" type="submit">Get Started</button>
                        <div class="description">
                        <small>Free 14-day trial · Easy setup · Cancel any time. Check out </small>
                        <a href="">Terms of Use.</a>
                        </div>
                    </form>
                    </div>
                </div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
export default {
  name: 'pricing-page',
  data() {
    return {
    }
  }
}
</script>
<style lang="scss">
    header {
        background: #ffffff;
        max-height: 80px;
        padding: 5px 130px;
    }
    .section-pricing-top {
        background: #F2F2F2;
        .head {
            padding-top: 80px;
            background-image: linear-gradient( #bfc0c1 0%, #F2F2F2 20%);
            text-align: center;
            position: relative;
            h1 {
                font-weight: bold;
                font-size: 56px;
                line-height: 56px;
                letter-spacing: -0.5px;
            }
            p {
                margin-top: 20px;
                font-size: 24px;
                line-height: 34px;
            }
        }
        .items {
            padding: 50px 130px;
            .card {
                background: #F2F2F2;
                &:hover {
                    background: #ffffff;
                    .card-nav {
                        // display: block;
                    }
                    .card-head {
                        button {
                            color: #ffffff;
                            background: #3041C5;
                        }
                    }
                }
                .card-nav {
                    display: none;
                    text-align: center;
                    padding: 20px;
                    border-bottom: 1px solid rgba(10, 10, 10, 0.1);
                    b {
                        color: #E22729;
                        font-size: 18px;
                    }
                    small {
                        color: rgba(43, 41, 45, 0.6);
                        font-size: 18px;
                    }
                }
                .card-head {
                    padding: 20px 0;
                    text-align: center;
                    min-height: 400px;
                    border-bottom: 1px solid rgba(10, 10, 10, 0.1);
                    span {
                        display: inline-block;
                    }
                    small {
                        display: inline-block;
                    }
                    button {
                        font-weight: bold;
                        color: #3041C5;
                        font-size: 18px;
                        line-height: 13px;
                        margin: 20px auto;
                        display: block;
                        border: 1px solid #3041C5;
                        border-radius: 2px;
                        width: 80%;
                        background: #F2F2F2;
                        padding: 15px;
                    }
                }
                .card-body {
                    min-height: 300px;
                    padding: 20px;
                    ul {
                        li {
                            list-style-image: url('~assets/image/ic-check.png');
                        }
                    }
                }
             }
        }
    }
    .section-pricing-question {
        padding: 50px 130px;
        .head {
            text-align: center;
            h1 {
                letter-spacing: -0.5px;
                font-weight: bold;
                font-size: 56px;
            }
        }
        .faq {
            margin-top: 40px;
            .columns {
                margin-top: 40px;
                h3 {
                    font-weight: bold;
                    font-size: 24px;
                }
                p {
                    margin-top: 10px;
                    font-size: 22px;
                    b {
                        color: #3041C5;
                    }
                }
            }
        }
    }

    @media screen and (max-width: 800px){
        header {
            padding: 0;
            background: #ffffff;
        }
        .section-pricing-top {
            .items {
                padding: 20px;
            }
        }
        .section-pricing-question {
            padding: 20px;
        }
    }
</style>