<script setup>
// example component
import HorizontalTeamCard from "@/examples/cards/teamCards/HorizontalTeamCard.vue";
import TeamCard2 from "../../../../examples/cards/teamCards/TeamCard2.vue";
// images
import chang from "@/assets/img/team/chang2.jpg";
import kexuan from "@/assets/img/team/tang_kexuan.png";
import yuliang from "@/assets/img/team/wang_yuliang.jpg";
</script>

<template>
  <section class="pb-5 position-relative bg-gradient-green  mx-n3">
    <div class="container">
      <div class="row">
        <div class="col-md-8 text-start mb-5 mt-5">
          <h3 class="text-black z-index-1 position-relative">
            Our R&D Team
          </h3>
          <p class="text-black opacity-8 mb-0">
            There’s nothing I really wanted to do in life that I wasn’t able to
            get good at. That’s my skill.
          </p>
        </div>
      </div>
      <div class="row mt-4">
        <div class="col-lg-9 col-12" >
          <HorizontalTeamCard
            class="mt-4 z-index-2 team-card-gradient"
            :image="kexuan"
            :profile="{ name: 'Tang Kexuan', link: 'javascript:;' }"
            :position="{ label: 'Researcher', color: 'success' }"
            description="Artist is a term applied to a person who engages in an
                    activity deemed to be an art."
          />
        </div>
      </div>
      <div class="row">
        <div class="col-lg-9 col-12 ">
          <TeamCard2
            class="mt-4 z-index-2 team-card-gradient"
            :image="yuliang"
            :profile="{ name: 'Wang Yuliang', link: 'javascript:;' }"
            :position="{ label: 'Researcher', color: 'success' }"
            description="Artist is a term applied to a person who engages in an
                    activity deemed to be an art."
          />
        </div>
      </div>
      <div class="row">
        <div class="col-lg-9 col-12">
          <HorizontalTeamCard
            class="mt-4 z-index-2 team-card-gradient"
            :image="chang"
            :profile="{ name: 'Chang xxxx', link: 'javascript:;' }"
            :position="{ label: 'Director', color: 'success' }"
            description="Artist is a term applied to a person who engages in an
                    activity deemed to be an art."
          />
        </div>
      </div>
    </div>
  </section>
</template>
