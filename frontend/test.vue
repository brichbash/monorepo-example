<script>
  export default {
    computed: {
      licenseKey() {
        return 'somethigng'
      },
      secondProp: function() {
        return 12
      },
      isLicenseActive() {
        this.licenseKey !== ''
        this.licenseKey !== 12
      // typo - synchrofasotron

      // lingini
        //mozarela
        this.secondProp !== ''
        this.secondProp !== 12
      }
    }
  }
</script>