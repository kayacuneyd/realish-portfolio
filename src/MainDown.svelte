<script>
  let edus = [
    {
      titleOfInst: "YTU",
      timeSpan: "2011-2016",
      subject: "Political Science & Int. Relations",
    },
    {
      titleOfInst: "Bielefeld University",
      timeSpan: "2014-2015",
      subject: "Sociology",
    },
    {
      titleOfInst: "University of Tartu",
      timeSpan: "2017- -",
      subject: "EU-Russia Studies",
    },
    {
      titleOfInst: "Münster University",
      timeSpan: "2019-2020",
      subject: "Political Science",
    },
  ];
</script>

<div class="w3-container w3-card w3-white">
  <h2 class="w3-text-grey w3-padding-16">
    <i
      class="fa fa-certificate fa-fw w3-margin-right w3-xxlarge w3-text-blue"
    />Education
  </h2>
  {#each edus as edu}
    <div class="w3-container">
      <h5 class="w3-opacity"><b>{edu.titleOfInst}</b></h5>
      <h6 class="w3-text-blue">
        <i class="fa fa-calendar fa-fw w3-margin-right" />{edu.timeSpan}
      </h6>
      <p>{edu.subject}</p>
      <hr />
    </div>
  {/each}
</div>
