<script>
  export let nickname
  export let name
</script>

<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <img src="https://scontent.faqp2-3.fna.fbcdn.net/v/t1.0-9/72690465_2574845069259101_2647251144983707648_n.jpg?_nc_cat=105&ccb=2&_nc_sid=09cbfe&_nc_eui2=AeEuXXjGPN8N4BXHgwa0wu7YwIrALFH22VDAisAsUfbZUMjJnioVoWgeCsgG1hD5yNSEvWgtYMyV1_lPdzPC2Dbf&_nc_ohc=_L0ycqIxB00AX_Jn75g&_nc_ht=scontent.faqp2-3.fna&oh=3a24e4a15f05ecdec77f7fb863589a50&oe=5FD52675" alt="logo">
    </div>
    <div class="Profile-info">
      <h2>@jocgts</h2>
      <span>Jose Gutierrez</span>
    </div>
  </div>
</div>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>