# Function: <code>igmp_group_dropped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff817973a0)
Location: net/ipv4/igmp.c:1186
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff817973a0-ffffffff817975f2: igmp_group_dropped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81804ae0)
Location: net/ipv4/igmp.c:1185
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
```
**Symbols:**

```
ffffffff81804ae0-ffffffff81804d48: igmp_group_dropped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81835ab0)
Location: net/ipv4/igmp.c:1216
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
```
**Symbols:**

```
ffffffff81835ab0-ffffffff81835d18: igmp_group_dropped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81856ff0)
Location: net/ipv4/igmp.c:1225
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
```
**Symbols:**

```
ffffffff81856ff0-ffffffff8185723a: igmp_group_dropped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d6ea0)
Location: net/ipv4/igmp.c:1253
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
```
**Symbols:**

```
ffffffff818d6ea0-ffffffff818d70ea: igmp_group_dropped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192d7e0)
Location: net/ipv4/igmp.c:1253
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
```
**Symbols:**

```
ffffffff8192d7e0-ffffffff8192da3b: igmp_group_dropped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void igmp_group_dropped(struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195cd90)
Location: net/ipv4/igmp.c:1264
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
  - net/ipv4/igmp.c:ip_mc_dec_group
```
**Symbols:**

```
ffffffff8195cd90-ffffffff8195cfeb: igmp_group_dropped (STB_LOCAL)
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
In net/ipv4/igmp.c (ffffffff819c3816)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff819fa3b6)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81ae8ca6)
Location: net/ipv4/igmp.c:1314
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81af5bb6)
Location: net/ipv4/igmp.c:1314
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81ae1306)
Location: net/ipv4/igmp.c:1321
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81ba09c6)
Location: net/ipv4/igmp.c:1321
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81d32ea6)
Location: net/ipv4/igmp.c:1327
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81efb166)
Location: net/ipv4/igmp.c:1327
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81f5abf6)
Location: net/ipv4/igmp.c:1328
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff82021136)
Location: net/ipv4/igmp.c:1330
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffff800010cb1aa0)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (c0dbd6c4)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (c000000000dc8a40)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffe00080a494)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff8199a156)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81953c16)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81a049f6)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
In net/ipv4/igmp.c (ffffffff81a0ef86)
Location: net/ipv4/igmp.c:1316
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_unmap
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
</ul>
