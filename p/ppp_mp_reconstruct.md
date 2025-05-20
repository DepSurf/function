# Function: <code>ppp_mp_reconstruct</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f6ff3)
Location: drivers/net/ppp/ppp_generic.c:2115
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8165716c)
Location: drivers/net/ppp/ppp_generic.c:2328
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81684e4c)
Location: drivers/net/ppp/ppp_generic.c:2367
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169a283)
Location: drivers/net/ppp/ppp_generic.c:2381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81704a33)
Location: drivers/net/ppp/ppp_generic.c:2408
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8174316b)
Location: drivers/net/ppp/ppp_generic.c:2391
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817679a5)
Location: drivers/net/ppp/ppp_generic.c:2439
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff817a3300-ffffffff817a367f: ppp_mp_reconstruct (STB_LOCAL)
ffffffff817a7839-ffffffff817a79ce: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff817c6d50-ffffffff817c70cf: ppp_mp_reconstruct (STB_LOCAL)
ffffffff817cb2a9-ffffffff817cb43e: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2523
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff818929d0-ffffffff81892d77: ppp_mp_reconstruct (STB_LOCAL)
ffffffff818958b3-ffffffff81895a50: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2671
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff818a0a70-ffffffff818a0e17: ppp_mp_reconstruct (STB_LOCAL)
ffffffff81c1998b-ffffffff81c19b25: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2704
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff81883100-ffffffff818834a7: ppp_mp_reconstruct (STB_LOCAL)
ffffffff81c0b7e2-ffffffff81c0b97c: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2709
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff81914aa0-ffffffff81914e47: ppp_mp_reconstruct (STB_LOCAL)
ffffffff81d10e27-ffffffff81d10fc1: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2710
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff81a6a0c0-ffffffff81a6a487: ppp_mp_reconstruct (STB_LOCAL)
ffffffff81edbb86-ffffffff81edbd1f: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcce0)
Location: drivers/net/ppp/ppp_generic.c:2712
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff81bfcce0-ffffffff81bfd1f2: ppp_mp_reconstruct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c62360)
Location: drivers/net/ppp/ppp_generic.c:2712
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff81c62360-ffffffff81c62872: ppp_mp_reconstruct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18d80)
Location: drivers/net/ppp/ppp_generic.c:2712
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
```
**Symbols:**

```
ffffffff81d18d80-ffffffff81d19292: ppp_mp_reconstruct (STB_LOCAL)
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
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff8000109fdf88)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffff8000109fdf88-ffff8000109fe410: ppp_mp_reconstruct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0adb878)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
c0adb878-c0adbd5c: ppp_mp_reconstruct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aa58a0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
c000000000aa58a0-c000000000aa5f38: ppp_mp_reconstruct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062b84e)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffe00062b84e-ffffffe00062bc1a: ppp_mp_reconstruct (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff8178b830-ffffffff8178bbaf: ppp_mp_reconstruct (STB_LOCAL)
ffffffff8178fd89-ffffffff8178ff1e: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff81774600-ffffffff8177497f: ppp_mp_reconstruct (STB_LOCAL)
ffffffff81778b59-ffffffff81778cee: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff817bbbd0-ffffffff817bbf4f: ppp_mp_reconstruct (STB_LOCAL)
ffffffff817c0129-ffffffff817c02be: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ppp_mp_reconstruct(struct ppp *ppp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:2435
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
**Symbols:**

```
ffffffff817d5e20-ffffffff817d619f: ppp_mp_reconstruct (STB_LOCAL)
ffffffff817da3dc-ffffffff817da571: ppp_mp_reconstruct.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
