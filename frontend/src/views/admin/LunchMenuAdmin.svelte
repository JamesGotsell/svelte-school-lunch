<script>
  let myDate = new Date().getTime();
  import { user } from "../../stores";
</script>

<div>
  <h1 class="title is-4">
    Admin is {$user.name} at {$user.schoolName}
    {myDate}
  </h1>
</div>
