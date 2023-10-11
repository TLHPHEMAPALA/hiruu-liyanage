### HI HELLOW 👋

<!--
**hiruu-liyanage/hiruu-liyanage** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
### I am Frontend Developer and Creative Designer 😄 

[![An image of @tlhphemapala's Holopin badges, which is a link to view their full Holopin profile](https://holopin.me/tlhphemapala)](https://holopin.io/@tlhphemapala)

import Image from "next/image";
import Link from "next/link";
import React, { forwardRef } from "react";

const HolopinImage = ({ user }, ref) => (
  <a ref={ref}>
    <Image
      src={`[https://holopin.me/${user](https://www.holopin.io/@tlhphemapala#)}`}
      alt={`[@${user}'s Holopin board](https://www.holopin.io/@tlhphemapala#badges)`}
      width={2428}
      height={764}
    />
  </a>
);

const HolopinRef = forwardRef(HolopinImage);

const Holopin = ({ user }) => (
  <div>
    <Link href={`[https://holopin.io/@${user}](https://www.holopin.io/@tlhphemapala#badges)`}>
      <HolopinRef user={user} />
    </Link>
  </div>
);
