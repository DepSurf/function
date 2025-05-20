# Function: <code>igmpv3_del_delrec</code>

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
In net/ipv4/igmp.c (ffffffff81796d37)
Location: net/ipv4/igmp.c:1124
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
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
In net/ipv4/igmp.c (ffffffff81805bc1)
Location: net/ipv4/igmp.c:1123
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81836730)
Location: net/ipv4/igmp.c:1141
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff81836730-ffffffff81836862: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81857f40)
Location: net/ipv4/igmp.c:1150
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff81857f40-ffffffff8185806c: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d7a70)
Location: net/ipv4/igmp.c:1178
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff818d7a70-ffffffff818d7b9c: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192e410)
Location: net/ipv4/igmp.c:1178
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
**Symbols:**

```
ffffffff8192e410-ffffffff8192e53f: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195d950)
Location: net/ipv4/igmp.c:1189
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
**Symbols:**

```
ffffffff8195d950-ffffffff8195da7f: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c2cb0)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff819c2cb0-ffffffff819c2def: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f9850)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff819f9850-ffffffff819f998f: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae6ae0)
Location: net/ipv4/igmp.c:1204
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81ae6ae0-ffffffff81ae6c8b: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af3920)
Location: net/ipv4/igmp.c:1204
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81af3920-ffffffff81af3acb: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81adef80)
Location: net/ipv4/igmp.c:1211
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81adef80-ffffffff81adf12b: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9e460)
Location: net/ipv4/igmp.c:1211
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81b9e460-ffffffff81b9e60b: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d30780)
Location: net/ipv4/igmp.c:1214
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81d30780-ffffffff81d30951: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef88f0)
Location: net/ipv4/igmp.c:1214
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81ef88f0-ffffffff81ef8ac1: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f58360)
Location: net/ipv4/igmp.c:1215
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81f58360-ffffffff81f58531: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201e820)
Location: net/ipv4/igmp.c:1217
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff8201e820-ffffffff8201e9f1: igmpv3_del_delrec (STB_LOCAL)
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
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010caf128)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffff800010caf128-ffff800010caf34c: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0db97d0)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
c0db97d0-c0db991c: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc3330)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
c000000000dc3330-c000000000dc3578: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe000806ec0)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffe000806ec0-ffffffe000806ff8: igmpv3_del_delrec (STB_LOCAL)
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
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819995f0)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff819995f0-ffffffff8199972f: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819530b0)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff819530b0-ffffffff819531ef: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a03e90)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81a03e90-ffffffff81a03fcf: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device *in_dev, struct ip_mc_list *im);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0e400)
Location: net/ipv4/igmp.c:1206
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_remap
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81a0e400-ffffffff81a0e53f: igmpv3_del_delrec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
