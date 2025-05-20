# Function: <code>scsi_device_quiesce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815aebf0)
Location: drivers/scsi/scsi_lib.c:2869
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff815aebf0-ffffffff815aec2d: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81606e70)
Location: drivers/scsi/scsi_lib.c:2743
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff81606e70-ffffffff81606eba: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816365e0)
Location: drivers/scsi/scsi_lib.c:2817
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff816365e0-ffffffff8163662a: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164b400)
Location: drivers/scsi/scsi_lib.c:2889
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff8164b400-ffffffff8164b46b: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b39b0)
Location: drivers/scsi/scsi_lib.c:2971
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff816b39b0-ffffffff816b3a51: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816efa80)
Location: drivers/scsi/scsi_lib.c:2987
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff816efa80-ffffffff816efb21: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817131a0)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff817131a0-ffffffff8171324d: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174ea70)
Location: drivers/scsi/scsi_lib.c:2499
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff8174ea70-ffffffff8174eb1d: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772c20)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff81772c20-ffffffff81772ccd: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81835100)
Location: drivers/scsi/scsi_lib.c:2529
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff81835100-ffffffff818351ad: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845a40)
Location: drivers/scsi/scsi_lib.c:2535
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff81845a40-ffffffff81845aed: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828cd0)
Location: drivers/scsi/scsi_lib.c:2552
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff81828cd0-ffffffff81828d7d: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b46b0)
Location: drivers/scsi/scsi_lib.c:2545
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff818b46b0-ffffffff818b475d: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819ff6f0)
Location: drivers/scsi/scsi_lib.c:2611
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
```
**Symbols:**

```
ffffffff819ff6f0-ffffffff819ff7a7: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7dce0)
Location: drivers/scsi/scsi_lib.c:2616
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81b7dce0-ffffffff81b7dd97: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd1a60)
Location: drivers/scsi/scsi_lib.c:2632
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81bd1a60-ffffffff81bd1b17: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c266d0)
Location: drivers/scsi/scsi_lib.c:2629
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81c266d0-ffffffff81c26787: scsi_device_quiesce (STB_GLOBAL)
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
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff8000109760f8)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffff8000109760f8-ffff8000109761b4: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4aaa0)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
c0a4aaa0-c0a4aba8: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a30770)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
c000000000a30770-c000000000a30870: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005de848)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffe0005de848-ffffffe0005de8ea: scsi_device_quiesce (STB_GLOBAL)
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
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81727310)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff81727310-ffffffff817273bd: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700740)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff81700740-ffffffff817007ed: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817660e0)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff817660e0-ffffffff8176618d: scsi_device_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_device_quiesce(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81781790)
Location: drivers/scsi/scsi_lib.c:2546
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_quiesce_fn
```
**Symbols:**

```
ffffffff81781790-ffffffff8178183d: scsi_device_quiesce (STB_GLOBAL)
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
