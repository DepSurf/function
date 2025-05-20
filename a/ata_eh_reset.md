# Function: <code>ata_eh_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d7960)
Location: drivers/ata/libata-eh.c:2637
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815d7960-ffffffff815d8619: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81631560)
Location: drivers/ata/libata-eh.c:2728
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81631560-ffffffff81632277: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816626b0)
Location: drivers/ata/libata-eh.c:2728
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816626b0-ffffffff816633c7: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81676f20)
Location: drivers/ata/libata-eh.c:2683
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81676f20-ffffffff81677c40: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816e0550)
Location: drivers/ata/libata-eh.c:2681
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816e0550-ffffffff816e127f: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171ce20)
Location: drivers/ata/libata-eh.c:2659
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8171ce20-ffffffff8171db17: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173f700)
Location: drivers/ata/libata-eh.c:2655
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8173f700-ffffffff817403f7: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8177ded6-ffffffff8177def0: ata_eh_reset.cold (STB_LOCAL)
ffffffff8177b530-ffffffff8177c214: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179f0a0)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8179f0a0-ffffffff8179fd99: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81863b10)
Location: drivers/ata/libata-eh.c:2442
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81863b10-ffffffff818648bd: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81872910)
Location: drivers/ata/libata-eh.c:2442
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81872910-ffffffff818736bd: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81854f30)
Location: drivers/ata/libata-eh.c:2442
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81854f30-ffffffff81855cd6: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e3460)
Location: drivers/ata/libata-eh.c:2449
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff818e3460-ffffffff818e42b3: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:2439
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81ed884c-ffffffff81ed8aae: ata_eh_reset.cold (STB_LOCAL)
ffffffff81a344a0-ffffffff81a3564d: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb8d00)
Location: drivers/ata/libata-eh.c:2445
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81bb8d00-ffffffff81bba133: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c105a0)
Location: drivers/ata/libata-eh.c:2555
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c105a0-ffffffff81c119c8: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c657e0)
Location: drivers/ata/libata-eh.c:2562
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c657e0-ffffffff81c66baf: ata_eh_reset (STB_GLOBAL)
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
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109aaa38)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffff8000109aaa38-ffff8000109ab794: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a7a374)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c0a7a374-c0a7b078: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a717f0)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a717f0-c000000000a7272c: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe0006083f2)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0006083f2-ffffffe000608eca: ata_eh_reset (STB_GLOBAL)
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
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81764190)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81764190-ffffffff81764e89: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81743ff0)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81743ff0-ffffffff81744ce9: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81793f20)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81793f20-ffffffff81794c19: ata_eh_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ata_eh_reset(struct ata_link *link, int classify, ata_prereset_fn_t prereset, ata_reset_fn_t softreset, ata_reset_fn_t hardreset, ata_postreset_fn_t postreset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817add90)
Location: drivers/ata/libata-eh.c:2640
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff817add90-ffffffff817aea89: ata_eh_reset (STB_GLOBAL)
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
