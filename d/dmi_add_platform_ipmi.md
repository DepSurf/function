# Function: <code>dmi_add_platform_ipmi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dmi_add_platform_ipmi(long unsigned int base_addr, u32 flags, u8 slave_addr, int irq, int offset, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/ipmi/ipmi_dmi.c (ffffffff820ea374)
Location: drivers/char/ipmi/ipmi_dmi.c:25
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
```
**Symbols:**

```
ffffffff820ea374-ffffffff820ea69f: dmi_add_platform_ipmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dmi_add_platform_ipmi(long unsigned int base_addr, u32 flags, u8 slave_addr, int irq, int offset, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/ipmi/ipmi_dmi.c (ffffffff826f3213)
Location: drivers/char/ipmi/ipmi_dmi.c:41
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
```
**Symbols:**

```
ffffffff826f3213-ffffffff826f35ff: dmi_add_platform_ipmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dmi_add_platform_ipmi(long unsigned int base_addr, u32 flags, u8 slave_addr, int irq, int offset, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/ipmi/ipmi_dmi.c (ffffffff8271d193)
Location: drivers/char/ipmi/ipmi_dmi.c:32
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
```
**Symbols:**

```
ffffffff8271d193-ffffffff8271d5d5: dmi_add_platform_ipmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dmi_add_platform_ipmi(long unsigned int base_addr, u32 flags, u8 slave_addr, int irq, int offset, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828d51a8)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: False
Direct callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
```
**Symbols:**

```
ffffffff828d51a8-ffffffff828d55db: dmi_add_platform_ipmi (STB_LOCAL)
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828ef38d)
Location: drivers/char/ipmi/ipmi_dmi.c:36
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828f851d)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff82d0f5c1)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff82ffd042)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff83207e68)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff832eff2b)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff834a8083)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff83edf33e)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff83704d9c)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff839382a8)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffff80001147b55c)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (c1553bc8)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828e1289)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828d9714)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828f4119)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
In drivers/char/ipmi/ipmi_dmi.c (ffffffff828f9571)
Location: drivers/char/ipmi/ipmi_dmi.c:35
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
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
</ul>
