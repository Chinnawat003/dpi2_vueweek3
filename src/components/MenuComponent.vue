<template lang="en">
    <nav class="navbar navbar-expand-lg shadow"  style="background-color:#CCCCFF">
        <div class="container-fluid">
          <router-link class="navbar-brand" to="/">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto  mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  เกี่ยวกับเรา
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">ประวัติส่วนตัว</a></li>
                  <li><a class="dropdown-item" href="#">วิสัยทัศน์</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">ที่อยู่</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" to="/">ติดต่อเรา</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>
<script>
export default {
    
}
</script>

<style lang="">
    
</style>