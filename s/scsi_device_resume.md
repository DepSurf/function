# Function: <code>scsi_device_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815aeb80)
Location: drivers/scsi/scsi_lib.c:2893
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff815aeb80-ffffffff815aeba7: scsi_device_resume.part.29 (STB_LOCAL)
ffffffff815aebb0-ffffffff815aebca: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81606e55)
Location: drivers/scsi/scsi_lib.c:2767
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff81606e00-ffffffff81606e27: scsi_device_resume.part.27 (STB_LOCAL)
ffffffff81606e30-ffffffff81606e4a: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816365c5)
Location: drivers/scsi/scsi_lib.c:2841
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff81636570-ffffffff81636597: scsi_device_resume.part.32 (STB_LOCAL)
ffffffff816365a0-ffffffff816365ba: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164a620)
Location: drivers/scsi/scsi_lib.c:2918
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff8164a620-ffffffff8164a670: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3930)
Location: drivers/scsi/scsi_lib.c:3016
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff816b3930-ffffffff816b39a0: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816efa00)
Location: drivers/scsi/scsi_lib.c:3032
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff816efa00-ffffffff816efa70: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713260)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff81713260-ffffffff817132cc: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174eb30)
Location: drivers/scsi/scsi_lib.c:2547
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff8174eb30-ffffffff8174eba4: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772ce0)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff81772ce0-ffffffff81772d54: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81836325)
Location: drivers/scsi/scsi_lib.c:2577
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff818351c0-ffffffff81835234: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81846e05)
Location: drivers/scsi/scsi_lib.c:2583
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff81845b00-ffffffff81845b61: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81829fd5)
Location: drivers/scsi/scsi_lib.c:2600
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff81828d90-ffffffff81828df1: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b5d95)
Location: drivers/scsi/scsi_lib.c:2593
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff818b4770-ffffffff818b47d1: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a011d5)
Location: drivers/scsi/scsi_lib.c:2659
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff819ff7d0-ffffffff819ff83b: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f7b5)
Location: drivers/scsi/scsi_lib.c:2664
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81b7dde0-ffffffff81b7de4b: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd36d5)
Location: drivers/scsi/scsi_lib.c:2680
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81bd1b60-ffffffff81bd1bcb: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c28355)
Location: drivers/scsi/scsi_lib.c:2677
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_restore
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_thaw
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_resume
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81c267d0-ffffffff81c2683b: scsi_device_resume (STB_GLOBAL)
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
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff8000109761e8)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffff8000109761e8-ffff800010976260: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4abc4)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
c0a4abc4-c0a4ac30: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a30890)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
c000000000a30890-c000000000a30950: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005de914)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffe0005de914-ffffffe0005de97c: scsi_device_resume (STB_GLOBAL)
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
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817273d0)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff817273d0-ffffffff81727444: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700800)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff81700800-ffffffff81700874: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817661a0)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff817661a0-ffffffff81766214: scsi_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81781850)
Location: drivers/scsi/scsi_lib.c:2594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_resume_fn
```
**Symbols:**

```
ffffffff81781850-ffffffff817818c4: scsi_device_resume (STB_GLOBAL)
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
