# Function: <code>__mmc_select_powerclass</code>

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
In drivers/mmc/core/mmc.c (ffffffff816c39d9)
Location: drivers/mmc/core/mmc.c:772
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81726b68)
Location: drivers/mmc/core/mmc.c:820
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff8175980a)
Location: drivers/mmc/core/mmc.c:841
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81778068)
Location: drivers/mmc/core/mmc.c:865
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff817ee471)
Location: drivers/mmc/core/mmc.c:867
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff8183759d)
Location: drivers/mmc/core/mmc.c:869
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff8186356d)
Location: drivers/mmc/core/mmc.c:869
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818a76e6)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818d9b46)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:871
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff819aa650-ffffffff819aa7d5: __mmc_select_powerclass (STB_LOCAL)
ffffffff819ad544-ffffffff819ad569: __mmc_select_powerclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:878
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff819ad1f0-ffffffff819ad375: __mmc_select_powerclass (STB_LOCAL)
ffffffff81c2a6d9-ffffffff81c2a6fe: __mmc_select_powerclass.cold (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffffffff81992c32)
Location: drivers/mmc/core/mmc.c:878
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:881
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81a3d780-ffffffff81a3d962: __mmc_select_powerclass (STB_LOCAL)
ffffffff81d2d705-ffffffff81d2d749: __mmc_select_powerclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:888
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81baa990-ffffffff81baab9a: __mmc_select_powerclass (STB_LOCAL)
ffffffff81ef9b48-ffffffff81ef9b8c: __mmc_select_powerclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:888
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81d4db50-ffffffff81d4dd62: __mmc_select_powerclass (STB_LOCAL)
ffffffff820a97be-ffffffff820a97dd: __mmc_select_powerclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:888
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81db84b0-ffffffff81db868d: __mmc_select_powerclass (STB_LOCAL)
ffffffff8212abb7-ffffffff8212abcd: __mmc_select_powerclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __mmc_select_powerclass(struct mmc_card *card, unsigned int bus_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:896
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81e70920-ffffffff81e70afd: __mmc_select_powerclass (STB_LOCAL)
ffffffff8220c95f-ffffffff8220c975: __mmc_select_powerclass.cold (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffff800010b33fd4)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (c0c0ea84)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (c000000000c2e79c)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffe00070c606)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff8187d506)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818ce9a6)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818eb4c6)
Location: drivers/mmc/core/mmc.c:866
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
