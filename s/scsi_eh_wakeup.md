# Function: <code>scsi_eh_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815abb30)
Location: drivers/scsi/scsi_error.c:63
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
**Symbols:**

```
ffffffff815abb30-ffffffff815abbd1: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81603a60)
Location: drivers/scsi/scsi_error.c:63
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
**Symbols:**

```
ffffffff81603a60-ffffffff81603afa: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81633140)
Location: drivers/scsi/scsi_error.c:63
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
**Symbols:**

```
ffffffff81633140-ffffffff816331da: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81647ed0)
Location: drivers/scsi/scsi_error.c:65
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
**Symbols:**

```
ffffffff81647ed0-ffffffff81647f68: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816b0f50)
Location: drivers/scsi/scsi_error.c:65
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
```
**Symbols:**

```
ffffffff816b0f50-ffffffff816b0feb: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ed270)
Location: drivers/scsi/scsi_error.c:65
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
```
**Symbols:**

```
ffffffff816ed270-ffffffff816ed30a: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81710da0)
Location: drivers/scsi/scsi_error.c:65
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
```
**Symbols:**

```
ffffffff81710da0-ffffffff81710e38: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174d86b)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff8174d86b-ffffffff8174d88a: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff8174c1d0-ffffffff8174c255: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff817719eb)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff817719eb-ffffffff81771a0a: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff81770350-ffffffff817703d5: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81834131)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
**Symbols:**

```
ffffffff81834131-ffffffff81834150: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff81832c40-ffffffff81832cc5: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c167f9)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81c167f9-ffffffff81c16818: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff81843850-ffffffff818438c3: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c084d4)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81c084d4-ffffffff81c084f3: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff81826a00-ffffffff81826a73: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81d0c38e)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81d0c38e-ffffffff81d0c3ad: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff818b2350-ffffffff818b23c3: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81ed52cd)
Location: drivers/scsi/scsi_error.c:64
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81ed52cd-ffffffff81ed52ec: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff819fd3c0-ffffffff819fd460: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7b770)
Location: drivers/scsi/scsi_error.c:64
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81b7b770-ffffffff81b7b816: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcf480)
Location: drivers/scsi/scsi_error.c:64
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81bcf480-ffffffff81bcf526: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost, unsigned int busy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c240a0)
Location: drivers/scsi/scsi_error.c:64
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81c240a0-ffffffff81c2414e: scsi_eh_wakeup (STB_GLOBAL)
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
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010973558)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffff800010973558-ffff800010973630: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a48140)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
c0a48140-c0a48220: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2d0f0)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
c000000000a2d0f0-c000000000a2d1fc: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005dc528)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffe0005dc528-ffffffe0005dc5ee: scsi_eh_wakeup (STB_GLOBAL)
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
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff817260db)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff817260db-ffffffff817260fa: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff81724a40-ffffffff81724ac5: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ff50b)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff816ff50b-ffffffff816ff52a: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff816fde70-ffffffff816fdef5: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81764eab)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff81764eab-ffffffff81764eca: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff81763810-ffffffff81763895: scsi_eh_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_eh_wakeup(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8178052b)
Location: drivers/scsi/scsi_error.c:66
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
**Symbols:**

```
ffffffff8178052b-ffffffff8178054a: scsi_eh_wakeup.cold (STB_LOCAL)
ffffffff8177ee60-ffffffff8177eefa: scsi_eh_wakeup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int busy</code>
</li>
</ul>
</details>
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
