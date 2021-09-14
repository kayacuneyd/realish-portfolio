<script>
  let jobs = [
    {
      titleOfJob: "Co-founder",
      time: "2019- -",
      firm: "Flikoston Magazin",
      explanation:
        "Flikoston is where the variaty of ideas come together and reach out the people who seek the peace coming from harmony.",
    },
    {
      titleOfJob: "Founder",
      time: "2021- -",
      firm: "Flikoston OÜ",
      explanation:
        "Flikoston OÜ has been established to provide creative and solution-based answers to the clients in the field of web design & programming.",
    },
  ];
</script>

<div class="w3-container w3-card w3-white w3-margin-bottom">
  <h2 class="w3-text-grey w3-padding-16">
    <i
      class="fa fa-suitcase fa-fw w3-margin-right w3-xxlarge w3-text-blue"
    />Work Experience
  </h2>
  {#each jobs as job}
    <div class="w3-container">
      <h5 class="w3-opacity"><b>{job.titleOfJob}</b></h5>
      <h6 class="w3-text-blue">
        <i class="fa fa-calendar fa-fw w3-margin-right" />{job.time}
      </h6>
      <p>
        {job.explanation}
      </p>
      <hr />
    </div>
  {/each}
</div>
