<template>
    <div style="background:#F8F9FA;font-family: 'Open Sans', sans-serif;">
        <div class="col-md-8 m-auto">
        <nav class="navbar navbar-expand-lg navbar-light ">
            <div class="container-fluid">
                <a class="navbar-brand font-family" href="#">nullBrains</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent" style="margin-left:250px;font-size:14px">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#" style="color:#4F46E5 !important"> Home</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Blog</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                    </li>

                </ul>

                </div>
                <div class="d-flex d-m-none">
                    <p class="mb-0 mt-1 mr-5 pr-2">signin</p>
                    <button class="px-3  py-1" style="color:white;background:#4F46E5; border:none;border-radius:20px;margin-left:20px">Signup</button>
                </div>
            </div>
        </nav>
    </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    @media only screen and (max-width: 600px) {
        .d-m-none{
            display: none !important;
        }
        .navbar-collapse{
            margin-left: 0 !important;
        }
    }


    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700&display=swap');
        .font-family{
            font-family: 'Open Sans', sans-serif;
            font-weight:900;
            font-size:20px
        }
</style>