# Function: <code>vga_arb_select_default_device</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8270574a)
Location: drivers/gpu/vga/vgaarb.c:1405
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff8272f588)
Location: drivers/gpu/vga/vgaarb.c:1405
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff828e7fbd)
Location: drivers/gpu/vga/vgaarb.c:1405
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff82902802)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff8290ba0b)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vga_arb_select_default_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff82d20b22)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff82d20b22-ffffffff82d20ccf: vga_arb_select_default_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vga_arb_select_default_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8300e901)
Location: drivers/gpu/vga/vgaarb.c:1453
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff8300e901-ffffffff8300eaae: vga_arb_select_default_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vga_arb_select_default_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff83219895)
Location: drivers/gpu/vga/vgaarb.c:1468
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff83219895-ffffffff83219a92: vga_arb_select_default_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vga_arb_select_default_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff83303387)
Location: drivers/gpu/vga/vgaarb.c:1447
Inline: False
Direct callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
**Symbols:**

```
ffffffff83303387-ffffffff833035f4: vga_arb_select_default_device (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/gpu/vga/vgaarb.c (ffff80001149b200)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (c159c168)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (c0000000013af410)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffe0000344fa)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff828f33c8)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff828ea873)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff82906e06)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
In drivers/gpu/vga/vgaarb.c (ffffffff8290ca6d)
Location: drivers/gpu/vga/vgaarb.c:1454
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
