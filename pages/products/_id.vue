<template>
    <main>
        <!-- Breadcrumbs -->
        <div class="a-spacing-top-medium"></div>
        <div class="container-fluid">
            <div class="wayfinding-breadcrumbs-container">
                <ul class="a-unordered-list a-horizontal a-size-small">
                    <li>
                        <span class="a-list-item">
                            <a href="#" class="a-link-normal a-color-tertiary">Category</a>
                        </span>
                    </li>
                    <li>
                        <span class="a-list-item">></span>
                    </li>
                    <li>
                        <span class="a-list-item">
                            <a href="#" class="a-link-normal a-color-tertiary">Product Title</a>
                        </span>
                    </li>
                </ul>
            </div>
        </div>
        <div class="container-fluid">
            <div class="dp-container">
                <div class="row">
                    <!-- First 3 grid - Product Image and Author's section -->
                    <div class="col-lg-3 col-md-3 col-sm-4">
                        <div class="leftcol">
                            <!-- Image -->
                            <div class="imgBlock">
                                <div class="eBooksimg">
                                    <img src="/img/steve_jobs.jpg" alt="" class="img-fluid">
                                </div>
                            </div>
                            <!-- Follow Author -->
                            <div class="authorFollow">
                                <hr class="a-divider-normal"/>
                                <h1 class="authorFollowHeading">Follow the author</h1>
                                <div class="a-spacing-top-small">
                                    <div class="row">
                                        <!-- Author's image -->
                                        <div class="col-xl-3 col-lg-3 col-md-3 col-sm-3 col-3">
                                            <div class="smallAuthorImageContainer">
                                                <a href="#">
                                                    <img src="/img/steve_jobs.jpg" alt="" class="img-fluid">
                                                </a>
                                            </div>
                                        </div>
                                        <!-- Author's name -->
                                        <div class="col-xl-4 col-lg-3 col-md-3 col-sm-3 col-3">
                                            <div class="authorNameCol">
                                                <a href="#">Walter Isaacson</a>
                                            </div>
                                        </div>
                                        <!-- Author's Follow Button -->
                                        <div class="col-xl-5 col-lg-6 col-md-6 col-sm-6 col-6">
                                            <div class="authorBtn mt-2">
                                                <a href="#">
                                                    <span class="btnFollow">
                                                        <span class="a-btn-inner">
                                                            <button class="a-btn-text">+ Follow</button>
                                                        </span>
                                                    </span>
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                    <!-- Description -->
                    <div class="col-lg-6 col-md-6 col-sm-8">
                        <div class="centerCol">
                            <!-- Product Title -->
                            <div class="titleDiv">
                                <h1 class="productTitle">
                                    <span class="largeTitle">Harry Potter</span>
                                    <span class="smallTitle">Paperback</span>
                                </h1>
                            </div>
                            <!-- Author's name -->
                            <div class="bylineinfo">
                                by
                                <a href="#" class="authorName">Walter Issacson
                                    <i class="fa fa-chevrondown" style="font-size: 8px Important; color: #555 !important;"></i>
                                </a> (Author)
                            </div>
                            <div class="reviewGroup"></div>
                            <hr style="margin-top: 10px;">
                            <!-- A tags Dummy Data -->
                            <div class="mediaMatrix">
                                <div class="formats">
                                    <a href="#" class="link-expander">
                                        >
                                        <span class="tmmShowPrompt">See all 18 formats and editions</span>
                                    </a>
                                    <ul>
                                        <!-- Kindle -->
                                        <li class="swatchElement" style="width: 117px;">
                                            <span class="a-list-item">
                                                 <span class="a-button-toggle">
                                                     <span class="a-button-inner">
                                                         <a href="#" class="a-button-text">
                                                             <span>Kindle</span>
                                                             <br />
                                                             <span class="a-color-secondary">-</span>
                                                         </a>
                                                     </span>
                                                 </span>
                                                 <span class="tmm-olp-links"></span>
                                                 <span class="tmm-olp-links">
                                                     <a href="#" class="a-size-mini">
                                                         <span class="kcpAppBox">
                                                             <span class="a-declarative">
                                                                 Read with our
                                                                 <span class="a-text-bold">Free</span>
                                                             </span>
                                                         </span>
                                                     </a>
                                                 </span>
                                            </span>
                                        </li>
                                        <!-- Audible -->
                                        <li class="swatchElement" style="width: 117px;">
                                            <span class="a-list-item">
                                                 <span class="a-button-toggle">
                                                     <span class="a-button-inner">
                                                         <a href="#" class="a-button-text">
                                                            <span>
                                                                <img src="/img/audibleLogo.png" alt="" class="img-fluid" style="width: 20px;"/> 
                                                                 Audible
                                                            </span>
                                                             <br />
                                                             <span class="a-color-secondary">-</span>
                                                         </a>
                                                     </span>
                                                 </span>
                                                 <span class="tmm-olp-links"></span>
                                                 <span class="tmm-olp-links">
                                                     <a href="#" class="a-size-mini">
                                                         <span class="kcpAppBox">
                                                             <span class="a-declarative">
                                                                 Read with our
                                                                 <span class="a-text-bold">Free App</span> with your Audible Trial
                                                             </span>
                                                         </span>
                                                     </a>
                                                 </span>
                                            </span>
                                        </li>
                                        <!-- Paperback -->
                                        <li class="swatchElement" style="width: 117px;">
                                            <span class="a-list-item">
                                                 <span class="a-button-toggle">
                                                     <span class="a-button-inner">
                                                         <a href="#" class="a-button-text">
                                                             <span>Paperback</span>
                                                             <br />
                                                             <span class="a-color-secondary">-</span>
                                                         </a>
                                                     </span>
                                                 </span>
                                                 <span class="tmm-olp-links"></span>
                                            </span>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <!-- Description -->
                            <div class="bookDescription">
                                <div class="bookDescriptionInner">This book is awesome</div>
                            </div>
                            <!-- Product specification -->
                            <div class="aboutEbooksFeature">
                                <hr/>
                                <div class="row">
                                    <div class="col-sm-4 mb-1">
                                        <div class="a-declarative">
                                            Length: <span><a href="#">386 pages <i class="a-icon a-icon-popover"></i></a></span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>