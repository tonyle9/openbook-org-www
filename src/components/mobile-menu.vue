<template>
    <div class="mobile-menu" v-bind:class="{ 'mobile-menu--open': isOpen }">
        <section class="hero is-fullheight">
            <!-- Hero head: will stick at the top -->
            <div class="hero-head">
                <header class="navbar">
                    <div class="container">
                        <div class="navbar-brand">
                            <a class="navbar-item is-size-4 has-text-primary" href="https://open-book.org">
                                <strong>Open</strong>book.
                            </a>
                            <div class="navbar-close navbar-item">
                                <button class="button is-outlined is-borderless navbar-close__button has-text-primary"
                                        @click="closeMenu()">
                                    <span class="icon is-size-3">
                                        <i class="fas fa-times"></i>
                                    </span>
                                </button>
                            </div>
                        </div>
                    </div>
                </header>
            </div>

            <!-- Hero content: will be in the middle -->
            <div class="hero-body is-paddingless hero-body--mobile-menu">
                <div class="container">
                    <div class="columns is-mobile is-multiline">
                        <router-link to="home" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-border-top-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-home"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>Home</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </router-link>
                        <router-link to="about-us" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-info"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>About us</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </router-link>
                        <router-link to="manifesto" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-book-open"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>Manifesto</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </router-link>
                        <router-link to="contact-us" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-envelope"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>Contact us</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </router-link>
                        <router-link to="jobs" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-star"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>Jobs</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </router-link>
                        <router-link to="faq" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-question-circle"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>FAQ</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </router-link>
                        <router-link to="press" active-class="mobile-menu-item--active"
                                     class="column is-12 is-size-5 has-border-bottom-gray-lighter has-text-grey-dark mobile-menu-item">
                            <div class="columns is-mobile">
                                <div class="column is-3">
                                    <div class="columns is-mobile is-centered is-vcentered">
                                        <div class="column is-narrow">
                                            <span class="icon">
                                                <i class="fas fa-newspaper"></i>
                                            </span>
                                        </div>
                                    </div>
                                </div>
                                <div class="column">
                                    <div class="columns is-mobile">
                                        <div class="column">
                                            <span>Press</span>
                                        </div>
                                        <div class="column is-4">
                                            <div class="columns is-mobile is-centered is-vcentered">
                                                <div class="column is-narrow">
                                                    <i class="fas fa-chevron-right mobile-menu-item__chevron"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </router-link>
                    </div>
                </div>
            </div>
            <div class="hero-footer">
                <div class="hero is-small is-primary">
                    <div class="hero-body">
                        <div class="columns is-mobile is-multiline">
                            <div class="column is-12">
                                <div class="columns is-mobile is-vcentered">
                                    <div class="column">
                                        <a href="https://twitter.com/Openbook_org" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                            <span class="icon">
                                                <i class="fab fa-twitter"></i>
                                            </span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                    <div class="column">
                                        <a href="https://github.com/OpenBookOrg" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                            <span class="icon">
                                                <i class="fab fa-github"></i>
                                            </span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                    <div class="column">
                                        <a href="https://www.reddit.com/user/openbook_org" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                            <span class="icon">
                                                <i class="fab fa-reddit-alien"></i>
                                            </span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                    <div class="column">
                                        <a href="https://gitter.im/openbook-org/Lobby" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                            <span class="icon">
                                                <i class="fab fa-gitter"></i>
                                            </span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                    <div class="column">
                                        <a href="https://www.producthunt.com/posts/openbook" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                                    <span class="icon"><i class="fab fa-product-hunt"></i></span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                    <div class="column">
                                        <a href="https://www.linkedin.com/openbookorg/" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                                    <span class="icon"><i class="fab fa-linkedin-in"></i></span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                    <div class="column">
                                        <a href="https://www.facebook.com/openbookorg/" class="is-flex is-vcentered"
                                           target="_blank" rel="noopener noreferrer">
                                            <div class="columns is-mobile">
                                                <div class="column">
                                                    <span class="icon"><i class="fab fa-facebook-f"></i></span>
                                                </div>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<style lang="scss">
    .mobile-menu {
        overflow: hidden;
        z-index: 999;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        min-height:100%;
        height:auto;
        background: #fafafa;
        display: none;

        &--open {
            display: block;
        }

        @media (min-width: 1090px) {
            display: none !important;
        }
    }

    .mobile-menu-item {
        &--active {
            background: #eaeaea !important;
            font-weight: bold;

            .mobile-menu-item__chevron {
                display: none !important;
            }
        }
    }

    .hero-body--mobile-menu {
        overflow-y: scroll;
        overflow-x: hidden;
    }

    .navbar-close {
        cursor: pointer;
        display: block;
        height: 4.25rem;
        position: relative;
        width: 4.25rem;
        margin-left: auto;

        &__button {
            background: none !important;
            border-radius: 0 !important;
            height: 100% !important;
            width: 100% !important;
        }
    }

</style>

<script>
    import events from './../events';

    export default {
        name: 'ob-mobile-menu',
        data() {
            return {
                isOpen: false
            }
        },
        mounted() {
            const eventRemovers = [
                events.onWantsToOpenMenu(this.onWantsToOpenMenu),
                events.onWantsToCloseMenu(this.onWantsToCloseMenu)
            ];

            this.removeAllEvents = () => {
                eventRemovers.forEach(eventRemover => eventRemover());
            }
        },
        destroyed() {
            this.removeAllEvents();
        },
        watch:{
            $route (){
                this.closeMenu();
            }
        },
        methods: {
            onWantsToOpenMenu() {
                this.openMenu();
            },
            onWantsToCloseMenu() {
                this.closeMenu();
            },
            openMenu() {
                this.isOpen = true;
            },
            closeMenu() {
                this.isOpen = false;
            }
        }
    }
</script>
