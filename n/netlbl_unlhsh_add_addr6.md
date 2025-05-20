# Function: <code>netlbl_unlhsh_add_addr6</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180ef3b)
Location: net/netlabel/netlabel_unlabeled.c:290
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff818815cd)
Location: net/netlabel/netlabel_unlabeled.c:290
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5e7d)
Location: net/netlabel/netlabel_unlabeled.c:284
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc7ba)
Location: net/netlabel/netlabel_unlabeled.c:284
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff819623aa)
Location: net/netlabel/netlabel_unlabeled.c:284
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bbbbc)
Location: net/netlabel/netlabel_unlabeled.c:284
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2e2d)
Location: net/netlabel/netlabel_unlabeled.c:284
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62191)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a98d71)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlbl_unlhsh_add_addr6(struct netlbl_unlhsh_iface *iface, const struct in6_addr *addr, const struct in6_addr *mask, struct lsmblob *lsmblob);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94420)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: False
Direct callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81b94420-ffffffff81b9450d: netlbl_unlhsh_add_addr6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_unlhsh_add_addr6(struct netlbl_unlhsh_iface *iface, const struct in6_addr *addr, const struct in6_addr *mask, struct lsmblob *lsmblob);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4060)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: False
Direct callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81ba4060-ffffffff81ba414d: netlbl_unlhsh_add_addr6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b932da)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5fa7a)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01e2f)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6cef)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff820529df)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff821251fc)
Location: net/netlabel/netlabel_unlabeled.c:271
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffff800010d685b8)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (c0e66cec)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4fc8)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b8da)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38101)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4d21)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3fb1)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab033c)
Location: net/netlabel/netlabel_unlabeled.c:270
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
