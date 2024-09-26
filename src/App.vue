<template>
<div id="app">
  <div class="container-fluid">
      <div class="row">
        <!-- Sidebar -->
        <nav id="sidebar" class="col-md-2 d-md-block bg-light sidebar" 
             style="height: 1115px; width: 236px; background-color: #F6F6F6;">
          <img src="@/assets/car.svg" alt="old mt-4" class="position-absolute mb-5" 
               style="width: 123px; height: 26px; top: 30px; left: 52px;" />
               <br>
            <ul class="nav flex-column mt-5">
          <li class="nav-item active" style="margin-bottom: 8px;">
            <router-link class="nav-link active" to="/" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
             <i class="bi bi-house-door-fill"></i> Home
            </router-link>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-file-earmark-text"></i> Orders
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
             <i class="bi bi-star"></i> Reviews
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-person-circle"></i> Clients
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-building"></i> Companies
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-truck-flatbed"></i> Trucks
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-award"></i> Brands
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-globe2"></i> Cities
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-file-earmark-text"></i> Content Management
            </a>
          </li>
          <li class="nav-item dropdown" style="margin-bottom: 8px;">
            <a class="nav-link" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
             <i class="bi bi-shield-lock"></i> Permissions  <i class="bi bi-chevron-down" style="margin-left: 50px;"></i>
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-gear"></i> System Management
            </a>
          </li>
          <li class="nav-item" style="margin-bottom: 8px;">
            <a class="nav-link active" href="#" 
             style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
             onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
             onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
              <i class="bi bi-translate"></i> Translation
              </a>
              </li>
              <li class="nav-item"  style="margin-bottom: 8px;">
              <a class="nav-link active" href="#" 
               style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
               onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
               onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
                <i class="bi bi-wechat"></i> Contact
              </a>
              </li>
              <li class="nav-item"  style="margin-bottom: 8px;">
              <a class="nav-link active" href="#" 
               style="color: #353535; border-left: 4px solid transparent; border-radius: 0px;"
               onmouseover="this.style.color='#FBA81A'; this.style.borderLeft='4px solid #FBA81A'; this.style.borderRadius='4px';"
               onmouseout="this.style.color='#353535'; this.style.borderLeft='4px solid transparent'; this.style.borderRadius='0px';">
                <i class="bi bi-chat-square-dots"></i> Client Review
              </a>
              </li>
          </ul>
        </nav>

        <!-- constant desgin -->
        <main role="main" class="col-md-9 ms-sm-auto col-lg-10 px-4 mt-4">
          <header style="font-family: 'Poppins', sans-serif; font-size: 16px; font-weight: 600; line-height: 24px; text-align: left; position: relative;">
    <!-- Horizontal Layout for Dashboard and Icons -->
    <div class="d-flex justify-content-between" style="width: 100%; height: 24px;">
      <span>Dashboard Overview</span>
      <div class ="d-flex justfity-content-end">
        
        <button class="btn d-flex align-items-center" style="height: 34px; font-size: 20px; border: none; border-radius: 0px;">
  <i class="bi bi-bell" style="border-radius: 50%; padding: 5px; border: 2px solid transparent;"></i>
</button>
        
        <!-- Vertical line -->
        <div class="mx-0" style="border-left: 1px solid #ccc; height: 24px;"></div>
        
        <!-- Account button (now in place of Bell icon) -->
        <div class="dropdown">
          <button class="btn d-flex align-items-center" type="button" id="dropdownMenuButton" data-bs-toggle="dropdown" aria-expanded="false" style="height: 24px; border: none;">
            <img src="@/assets/gg.svg" alt="Profile" style="width: 40px; height: 34px; border-radius: 50%; margin-right: 8px;"/>
          <span style="font-family: 'Poppins', sans-serif; font-size:18px; margin-right: 10px; ">INGOUDE COMPANY</span>
          <i class="bi bi-chevron-down"></i>
        </button>
          <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
            <!-- Dropdown items here -->
            <li><a class="dropdown-item" href="#">Profile</a></li>
            <li><a class="dropdown-item" href="#">Settings</a></li>
            <li><a class="dropdown-item" href="#">Logout</a></li>
          </ul>
        </div>
    </div>
    </div>
    
    <!-- Current date below the dashboard header -->
    <div id="current-date" class="text-muted" style="font-size: 14px; font-weight: 400; margin-top: 5px;"></div>
    <form style="margin-top: 8px;">
  <div class="row d-flex align-items-center">
    <!-- First Radio Button -->
    <div class="col-auto">
      <input id="all1" type="radio" value="all" name="lang">
      <label for="all1" class="ms-2"> All </label>
    </div>

    <!-- Second Radio Button -->
    <div class="col-auto">
      <input id="all2" type="radio" value="all" name="lang">
    </div>

    <!-- Date Pickers in the Same Row -->
    <div class="col-auto d-flex align-items-center">
      <!-- "From" Date Picker -->
      <div class="input-group me-3">
        <span class="input-group-text bg-white border-end-0 border-start-0 d-flex align-items-center" style="width: 50px;">From</span>
        <span class="input-group-text vertical-line d-flex align-items-center border-start-0 border-end-0" style="padding-left: 10px;">|</span>
        <input type="date" class="form-control border-start-0 border-end-0" style="min-width: 110px;">
        <span class="input-group-text bg-white border-start-0 d-flex align-items-center" >
          <i class="bi bi-chevron-down"></i>
        </span>
      </div>

      <!-- "To" Date Picker -->
      <div class="input-group">
        <span class="input-group-text bg-white border-end-0 border-start-0 d-flex align-items-center" style="width: 30px;">To</span>
        <span class="input-group-text vertical-line d-flex align-items-center border-start-0 border-end-0" style="padding-left: 10px;">|</span>
        <input type="date" class="form-control border-start-0 border-end-0" style="min-width: 90px;">
        <span class="input-group-text bg-white border-start-0 d-flex align-items-center" >
          <i class="bi bi-chevron-down"></i>
        </span>
      </div>
    </div>
    <div class="col-auto">
        <button type="button" class="btn btn-warning text-white">Find</button>
      </div>
  </div>
</form>


  </header>


  <div class="container mt-4 flex-grow-1">
      <router-view />
    </div>
        </main>
      </div>
    </div>
</div>   
</template>
<script>
export default {
  name: 'App',
  mounted() {
    // Function to format the date
    const formatDate = (date) => {
      const options = { day: 'numeric', month: 'short', year: 'numeric' };
      return date.toLocaleDateString('en-GB', options); // Format: '16 Sep 2024'
    };

    // Get the current date and update it
    const updateDate = () => {
      const today = new Date();
      document.getElementById('current-date').textContent = formatDate(today);
    };

    // Initial date update
    updateDate();

    // Update the date every day at midnight
    const timeToMidnight = new Date().setHours(24, 0, 0, 0) - new Date();
    setTimeout(() => {
      updateDate();
      setInterval(updateDate, 24 * 60 * 60 * 1000); // Update every 24 hours
    }, timeToMidnight);
  }
};
</script>
<style scoped>
.bi-bell:hover {
    color: yellow; /* Change bell icon color to yellow */
    border-color: yellow; /* Add yellow border on hover */
    
  }
 
</style>