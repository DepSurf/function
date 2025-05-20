# Function: <code>__ipv6_addr_jhash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e337e)
Location: include/net/ipv6.h:565
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff81800706)
Location: include/net/ipv6.h:565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81801cae)
Location: include/net/ipv6.h:565
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8185190d)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff81871e26)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187301d)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818836cd)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff818a6406)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a763d)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818a995d)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff818cce56)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cdf3d)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192c30d)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff81951c46)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952d2d)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8198477d)
Location: include/net/ipv6.h:611
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff819ab1d5)
Location: include/net/ipv6.h:611
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac2bd)
Location: include/net/ipv6.h:611
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bae14)
Location: include/net/ipv6.h:603
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/output_core.c (ffffffff819e1cf5)
Location: include/net/ipv6.h:603
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e2e9d)
Location: include/net/ipv6.h:603
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a28cb6)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51c2d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a5f7fa)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8882d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b5931d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83e6d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b6794d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b936cd)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b55b2d)
Location: include/net/ipv6.h:662
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b827dd)
Location: include/net/ipv6.h:662
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1b5ed)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e8ad)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db7d0d)
Location: include/net/ipv6.h:719
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def1dd)
Location: include/net/ipv6.h:719
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f87d3d)
Location: include/net/ipv6.h:752
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc328d)
Location: include/net/ipv6.h:752
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81fea79d)
Location: include/net/ipv6.h:753
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202409d)
Location: include/net/ipv6.h:753
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b86bd)
Location: include/net/ipv6.h:753
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f320d)
Location: include/net/ipv6.h:753
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d23c84)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55444)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e29784)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (c0e559fc)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e55c28)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e25c)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe0008667a6)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cbee)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819fee8a)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a27ebd)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bbc4a)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4c7d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a6990a)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93a6d)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a75ee3)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fbbd)
Location: include/net/ipv6.h:661
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
</ul>

## Differences
