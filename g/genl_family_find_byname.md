# Function: <code>genl_family_find_byname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8174f1d0)
Location: net/netlink/genetlink.c:114
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff8174f1d0-ffffffff8174f234: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817bb1e0)
Location: net/netlink/genetlink.c:114
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff817bb1e0-ffffffff817bb250: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817eab80)
Location: net/netlink/genetlink.c:97
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff817eab80-ffffffff817eabfe: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8180ab00)
Location: net/netlink/genetlink.c:97
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff8180ab00-ffffffff8180ab7e: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81889a50)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff81889a50-ffffffff81889ace: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818dd530)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff818dd530-ffffffff818dd5ae: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81909ef0)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff81909ef0-ffffffff81909f6e: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8196b2d0)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff8196b2d0-ffffffff8196b348: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819a1c80)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff819a1c80-ffffffff819a1cf8: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7c79b)
Location: net/netlink/genetlink.c:98
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a86b61)
Location: net/netlink/genetlink.c:98
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
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
In net/netlink/genetlink.c (ffffffff81a6f0cb)
Location: net/netlink/genetlink.c:98
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
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
In net/netlink/genetlink.c (ffffffff81b28b0b)
Location: net/netlink/genetlink.c:90
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
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
In net/netlink/genetlink.c (ffffffff81cb1419)
Location: net/netlink/genetlink.c:90
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
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
In net/netlink/genetlink.c (ffffffff81e6fd0a)
Location: net/netlink/genetlink.c:120
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
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
In net/netlink/genetlink.c (ffffffff81ecb5da)
Location: net/netlink/genetlink.c:120
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
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
In net/netlink/genetlink.c (ffffffff81f8eaca)
Location: net/netlink/genetlink.c:132
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffff800010c50800)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffff800010c50800-ffff800010c5089c: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c0d604b8)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
c0d604b8-c0d60558: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c000000000d4f200)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
c000000000d4f200-c000000000d4f460: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffe0007bbdc4)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffe0007bbdc4-ffffffe0007bbe26: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81941af0)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff81941af0-ffffffff81941b68: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818fb5e0)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff818fb5e0-ffffffff818fb658: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81992c80)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff81992c80-ffffffff81992cf8: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct genl_family *genl_family_find_byname(char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819b5770)
Location: net/netlink/genetlink.c:98
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
```
**Symbols:**

```
ffffffff819b5770-ffffffff819b57e8: genl_family_find_byname (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct genl_family *</code> ➡️ <code>const struct genl_family *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
