<template>
  <Card
    v-for="(item, index) in books"
    :key="index"
    :title="item.title"
    :description="item.description"
    :image="item.image"
  ></Card>
</template>
<script>
import Card from "@/components/Card.vue";
export default {
  components: { Card },
  data() {
    return {
      books: [
        {
          title: "Le Cambodge",
          page: 454,
          author: "Jonh",
          image: "https://placehold.jp/150x150.png",
        },
        {
          title: "Histroy of Cambodia",
          page: 454,
          author: "Jonh",
          image: "https://placehold.jp/150x150.png",
        },
        {
          title: "Le Cambodge sdsf",
          page: 454,
          author: "Jonh",
          image: "https://placehold.jp/150x150.png",
        },
        {
          title: "Le Cambodge 242",
          page: 454,
          author: "Jonh",
          image: "https://placehold.jp/150x150.png",
        },
        {
          title: "Le Cambodge",
          page: 454,
          author: "Jonh",
          image: "https://placehold.jp/150x150.png",
        },
      ],
    };
  },
};
</script>