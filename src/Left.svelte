<script>
  let skills = ["HTML", "CSS", "JavaScript", "PHP", "WordPress", "Web Design"];
  let infos = [
    {
      titleOf: "WordPress & Frontend Developer",
      icon: "fa fa-briefcase",
    },
    {
      titleOf: "Istanbul, Turkey",
      icon: "fa fa-home",
    },
    {
      titleOf: "info@kayacuneyt.com",
      icon: "fa fa-envelope",
    },
  ];

  let morePersonalized = {
    name: "Cüneyt Kaya",
    photoPath: "/assets/img/photo-ck.jpg",
  };

  let langs = ["Turkish", "English", "German"];
</script>

<!-- Left Column -->
<div class="w3-third">
  <div class="w3-white w3-text-grey w3-card-4">
    <div class="w3-display-container">
      <img
        src={morePersonalized.photoPath}
        style="width:100%"
        alt="Photo of {morePersonalized.name}"
      />
      <div class="w3-display-bottomleft w3-container w3-text-white">
        <h2>{morePersonalized.name}</h2>
      </div>
    </div>
    <div class="w3-container">
      {#each infos as info}
        <p>
          <i
            class="{info.icon} fa-fw w3-margin-right w3-large w3-text-blue"
          />{info.titleOf}
        </p>
      {/each}
      <hr />

      <p class="w3-large">
        <b
          ><i class="fa fa-asterisk fa-fw w3-margin-right w3-text-blue" />
          Skills</b
        >
      </p>
      {#each skills as skill}
        <p>{skill}</p>
      {/each}

      <hr />
      <p class="w3-large w3-text-theme">
        <b
          ><i
            class="fa fa-globe fa-fw w3-margin-right w3-text-blue"
          />Languages</b
        >
      </p>
      {#each langs as lang}
        <p>{lang}</p>
      {/each}
      <br />
    </div>
  </div>
  <br />

  <!-- End Left Column -->
</div>
