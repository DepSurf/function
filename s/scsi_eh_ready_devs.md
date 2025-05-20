# Function: <code>scsi_eh_ready_devs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815aac90)
Location: drivers/scsi/scsi_error.c:2068
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff815aac90-ffffffff815ab951: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81602c10)
Location: drivers/scsi/scsi_error.c:2068
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81602c10-ffffffff8160388f: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81632300)
Location: drivers/scsi/scsi_error.c:2068
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81632300-ffffffff81632f7f: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81646ec0)
Location: drivers/scsi/scsi_error.c:1998
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81646ec0-ffffffff81647a9f: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816aff20)
Location: drivers/scsi/scsi_error.c:2023
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff816aff20-ffffffff816b0b0b: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ec2a0)
Location: drivers/scsi/scsi_error.c:2047
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff816ec2a0-ffffffff816ece43: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8170fde0)
Location: drivers/scsi/scsi_error.c:2044
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff8170fde0-ffffffff81710983: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174ba54)
Location: drivers/scsi/scsi_error.c:2064
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff8174d6ec-ffffffff8174d86b: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff8174b650-ffffffff8174c075: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8176fbd4)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff8177186c-ffffffff817719eb: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff8176f7d0-ffffffff817701f5: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81832b10)
Location: drivers/scsi/scsi_error.c:2069
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81832b10-ffffffff81832c3c: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81843720)
Location: drivers/scsi/scsi_error.c:2083
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81843720-ffffffff8184384c: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8182682b)
Location: drivers/scsi/scsi_error.c:2104
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81c08474-ffffffff81c084d4: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff818267c0-ffffffff818269f6: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b217b)
Location: drivers/scsi/scsi_error.c:2116
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81d0c32e-ffffffff81d0c38e: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff818b2110-ffffffff818b2346: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fd1f9)
Location: drivers/scsi/scsi_error.c:2121
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81ed526f-ffffffff81ed52cd: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff819fd180-ffffffff819fd3be: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7b4c0)
Location: drivers/scsi/scsi_error.c:2130
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81b7b4c0-ffffffff81b7b75c: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcf1d0)
Location: drivers/scsi/scsi_error.c:2175
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81bcf1d0-ffffffff81bcf46c: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c23df0)
Location: drivers/scsi/scsi_error.c:2178
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
```
**Symbols:**

```
ffffffff81c23df0-ffffffff81c2408c: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010972a20)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffff800010972a20-ffff800010973554: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a47280)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
c0a47280-c0a47fb0: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2c120)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
c000000000a2c120-c000000000a2cee0: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005db9fc)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffe0005db9fc-ffffffe0005dc376: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff817242c4)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81725f5c-ffffffff817260db: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff81723ec0-ffffffff817248e5: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fd6f4)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff816ff38c-ffffffff816ff50b: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff816fd2f0-ffffffff816fdd15: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81763094)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81764d2c-ffffffff81764eab: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff81762c90-ffffffff817636b5: scsi_eh_ready_devs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_ready_devs(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177e6f4)
Location: drivers/scsi/scsi_error.c:2067
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff817803ac-ffffffff8178052b: scsi_eh_ready_devs.cold (STB_LOCAL)
ffffffff8177e2f0-ffffffff8177ed15: scsi_eh_ready_devs (STB_GLOBAL)
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
