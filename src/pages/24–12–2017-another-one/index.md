---
path: "/another-one"
date: "2017-07-12T17:12:33.962Z"
title: "My Second Gatsby Post"
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis eros elit. Suspendisse tristique ut massa ac consectetur. In ac consequat nunc, non molestie lacus.
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam cupiditate magni ducimus accusamus vero, natus culpa eius beatae iure nobis ea id, illum temporibus eligendi quisquam adipisci totam sapiente fugit expedita alias doloremque optio voluptates error laudantium! Quos magni quasi voluptatibus facere ea totam dignissimos consequuntur cumque ipsum soluta, dolores modi libero rem ad natus dicta eveniet perspiciatis neque. Laboriosam vero ad, nam expedita. Facilis atque quam sed ad sint voluptatem nesciunt accusantium rerum, soluta nemo autem, pariatur distinctio quod eaque ullam saepe veritatis tempora minus facere laborum quo aliquam amet, dolor recusandae.

```javascript
{
  human(id: "1000") {
    name
    height
  }
}
```

```javascript
{
  "data": {
    "human": {
      "name": "Luke Skywalker",
      "height": 1.72
    }
  }
}
```

Dicta iusto quos numquam pariatur.

Veritatis facere quia ipsum aspernatur nulla! Eveniet placeat tempore impedit corporis consectetur. Dolores eveniet, dolor aspernatur quis harum consequatur quidem aliquam esse, natus, eaque dolore vitae ipsa provident distinctio. Distinctio, officia! Quisquam eius debitis perferendis voluptate numquam animi, fugit magnam asperiores fugiat quos officia libero facere aliquid quas. Maiores excepturi nostrum iste nam deserunt, odio praesentium quod, aperiam nemo temporibus, perspiciatis, omnis sint eligendi placeat dolorum voluptate voluptas nesciunt accusantium mollitia? Distinctio quae totam, incidunt unde aperiam. Saepe assumenda cumque quia architecto aliquid impedit, deleniti optio facilis accusantium vero consequuntur in natus tenetur ratione voluptatibus molestiae sapiente ipsum, quas nobis repudiandae aperiam!


```javascript
query Hero($episode: Episode, $withFriends: Boolean!) {
  hero(episode: $episode) {
    name
    friends @include(if: $withFriends) {
      name
    }
  }
}
```

```javascript
{
  "data": {
    "hero": {
      "name": "R2-D2"
    }
  }
}
```
