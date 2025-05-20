# Function: <code>ata_eh_link_report</code>

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
In drivers/ata/libata-eh.c (ffffffff815d70fe)
Location: drivers/ata/libata-eh.c:2428
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_report
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
In drivers/ata/libata-eh.c (ffffffff81630d9e)
Location: drivers/ata/libata-eh.c:2514
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_report
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
In drivers/ata/libata-eh.c (ffffffff81661eee)
Location: drivers/ata/libata-eh.c:2514
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816745b0)
Location: drivers/ata/libata-eh.c:2451
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff816745b0-ffffffff81674e12: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816ddc10)
Location: drivers/ata/libata-eh.c:2449
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff816ddc10-ffffffff816de472: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171a420)
Location: drivers/ata/libata-eh.c:2429
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff8171a420-ffffffff8171acaa: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173cd20)
Location: drivers/ata/libata-eh.c:2425
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff8173cd20-ffffffff8173d5aa: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81778860)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff81778860-ffffffff817790fd: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179c6d0)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff8179c6d0-ffffffff8179cf6d: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818603d0)
Location: drivers/ata/libata-eh.c:2212
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff818603d0-ffffffff81860c4d: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8186f1f0)
Location: drivers/ata/libata-eh.c:2212
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff8186f1f0-ffffffff8186fa6b: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81851a00)
Location: drivers/ata/libata-eh.c:2212
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff81851a00-ffffffff81852276: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818df720)
Location: drivers/ata/libata-eh.c:2219
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff818df720-ffffffff818e0096: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:2212
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff81a30bf0-ffffffff81a30d3c: ata_eh_link_report (STB_LOCAL)
ffffffff81ed78d5-ffffffff81ed835e: ata_eh_link_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb42a0)
Location: drivers/ata/libata-eh.c:2218
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff81bb42a0-ffffffff81bb4ea1: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0b790)
Location: drivers/ata/libata-eh.c:2328
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff81c0b790-ffffffff81c0c398: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c60960)
Location: drivers/ata/libata-eh.c:2335
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
```
**Symbols:**

```
ffffffff81c60960-ffffffff81c6156b: ata_eh_link_report (STB_LOCAL)
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
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a72e8)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffff8000109a72e8-ffff8000109a7b44: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a774fc)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
c0a774fc-c0a77e98: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6da70)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
c000000000a6da70-c000000000a6e70c: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000605bb0)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffe000605bb0-ffffffe0006064c6: ata_eh_link_report (STB_LOCAL)
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
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817617c0)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff817617c0-ffffffff8176205d: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81741620)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff81741620-ffffffff81741ebd: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81791550)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff81791550-ffffffff81791ded: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_eh_link_report(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817ab390)
Location: drivers/ata/libata-eh.c:2410
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_report
```
**Symbols:**

```
ffffffff817ab390-ffffffff817abc2d: ata_eh_link_report (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
