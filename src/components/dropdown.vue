<template>
  <div id="app">
          <v-app id="inspire">
            <div class="">
              <v-menu offset-y>
                <template v-slot:activator="{ on }">
                  <v-btn dark v-on="on">
                    About Lendbox
                  </v-btn>
                </template>
                <v-list>
                  <v-list-tile v-for="(item, index) in items" :key="index">
                    <v-list-tile-title>{{ item.title }}</v-list-tile-title>            
                  </v-list-tile>
                </v-list>
              </v-menu>
              <v-menu offset-y>
                <template v-slot:activator="{ on }">
                  <v-btn dark v-on="on">
                    Investors
                  </v-btn>
                </template>
                <v-list>
                  <v-list-tile v-for="(item, index) in items1" :key="index">
                    <v-list-tile-title>{{ item.title }}</v-list-tile-title>            
                  </v-list-tile>
                </v-list>
              </v-menu>
              <v-menu offset-y>
                <template v-slot:activator="{ on }">
                  <v-btn dark v-on="on">
                    Borrowers
                  </v-btn>
                </template>
                <v-list>
                  <v-list-tile v-for="(item, index) in items2" :key="index">
                    <v-list-tile-title>{{ item.title }}</v-list-tile-title>            
                  </v-list-tile>
                </v-list>
              </v-menu>
              <v-menu offset-y>
                <template v-slot:activator="{ on }">
                  <v-btn dark v-on="on">
                    Legal
                  </v-btn>
                </template>
                <v-list>
                  <v-list-tile v-for="(item, index) in items3" :key="index">
                    <v-list-tile-title>{{ item.title }}</v-list-tile-title>            
                  </v-list-tile>
                </v-list>
              </v-menu>
            </div>
          </v-app>
        </div>
</template>

<script>
export default {
     data:() => ({
    items: [
      { title: 'Home' },
      { title: 'How it works' },
      { title: 'About Us' },
      { title: "RBI's NBFC-P2P License" },
      { title: 'Blogs' },
      { title: 'Calculate EMI' },
      { title: 'Broad Business Model' },
      { title: 'Overview of Credit Methodology' }
    ],
    items1: [
      { title: 'Why Invest' },
      { title: 'Investors Eligibility' },
      { title: 'How to invest' },
      { title: "Return and fees" },
      { title: 'Investor code of conduct' },
      { title: "Investor's FAQ" },
      { title: 'Low risk alternate investments' },
      { title: 'Tutorial for investors' }
    ],
    items2: [
      { title: 'Why Borrow' },
      { title: 'Borrowers Eligibility' },
      { title: 'How to create effective listing' },
      { title: "Purpose of Loan" },
      { title: 'Repayament, Interest Rates' },
      { title: "Borrower FAQ" },
      { title: 'Tutorial for Borrowers' }
    ],
    items3: [
      { title: 'Term of use' },
      { title: 'Privacy policy' },
      { title: 'Fair practice Code' },
      { title: "RBI Disclaimer" },
      { title: 'Grievence Redressal' }
    ]
  })

}
</script>

<style>

</style>