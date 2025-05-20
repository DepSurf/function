# Function: <code>scsi_restart_operations</code>

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
In drivers/scsi/scsi_error.c (ffffffff815ac8cb)
Location: drivers/scsi/scsi_error.c:2006
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816047d2)
Location: drivers/scsi/scsi_error.c:2006
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81633eb4)
Location: drivers/scsi/scsi_error.c:2006
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81648a66)
Location: drivers/scsi/scsi_error.c:1936
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816b1b70)
Location: drivers/scsi/scsi_error.c:1961
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816edf47)
Location: drivers/scsi/scsi_error.c:1985
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81711b32)
Location: drivers/scsi/scsi_error.c:1982
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8174cfe7)
Location: drivers/scsi/scsi_error.c:2002
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81771167)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void scsi_restart_operations(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2007
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81830d60-ffffffff81830ea9: scsi_restart_operations (STB_LOCAL)
ffffffff81833f8b-ffffffff81833faa: scsi_restart_operations.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void scsi_restart_operations(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2021
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff818419a0-ffffffff81841ae9: scsi_restart_operations (STB_LOCAL)
ffffffff81c16653-ffffffff81c16672: scsi_restart_operations.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2042
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81824ba0-ffffffff81824d96: scsi_restart_operations.constprop.0 (STB_LOCAL)
ffffffff81c0832c-ffffffff81c0834b: scsi_restart_operations.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2054
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff818b0420-ffffffff818b0616: scsi_restart_operations.constprop.0 (STB_LOCAL)
ffffffff81d0c1e6-ffffffff81d0c205: scsi_restart_operations.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2059
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff819fb4f0-ffffffff819fb6b6: scsi_restart_operations.constprop.0 (STB_LOCAL)
ffffffff81ed50fb-ffffffff81ed511b: scsi_restart_operations.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b795f0)
Location: drivers/scsi/scsi_error.c:2068
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81b795f0-ffffffff81b797d6: scsi_restart_operations.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcd280)
Location: drivers/scsi/scsi_error.c:2113
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81bcd280-ffffffff81bcd462: scsi_restart_operations.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c21eb0)
Location: drivers/scsi/scsi_error.c:2116
Inline: True
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81c21eb0-ffffffff81c22092: scsi_restart_operations.constprop.0 (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffff8000109745f4)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (c0a49050)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (c000000000a2e598)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffe0005dd142)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81725857)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816fec87)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81764627)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8177fca7)
Location: drivers/scsi/scsi_error.c:2005
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
