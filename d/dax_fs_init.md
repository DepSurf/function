# Function: <code>dax_fs_init</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dax_fs_init();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff820fa472)
Location: drivers/dax/super.c:585
Inline: True
```
**Symbols:**

```
ffffffff820fa472-ffffffff820fa536: dax_fs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dax_fs_init();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff82703c87)
Location: drivers/dax/super.c:614
Inline: True
```
**Symbols:**

```
ffffffff82703c87-ffffffff82703d4b: dax_fs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dax_fs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8272da0a)
Location: drivers/dax/super.c:640
Inline: False
```
**Symbols:**

```
ffffffff8272da0a-ffffffff8272dace: dax_fs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dax_fs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff828e63d3)
Location: drivers/dax/super.c:639
Inline: False
```
**Symbols:**

```
ffffffff828e63d3-ffffffff828e6497: dax_fs_init (STB_LOCAL)
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
In drivers/dax/super.c (ffffffff82900b75)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff82909d8f)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff82d1ffc8)
Location: drivers/dax/super.c:689
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff8300dda4)
Location: drivers/dax/super.c:697
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff83218bcf)
Location: drivers/dax/super.c:697
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff833025f8)
Location: drivers/dax/super.c:652
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff834bb824)
Location: drivers/dax/super.c:461
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff83ef9805)
Location: drivers/dax/super.c:526
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff8371f495)
Location: drivers/dax/super.c:529
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff83952e65)
Location: drivers/dax/super.c:530
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffff800011499550)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (c159a178)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (c0000000013ace30)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffe000032a5a)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff828f1134)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff828e84b7)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff829050b2)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
In drivers/dax/super.c (ffffffff8290adf1)
Location: drivers/dax/super.c:661
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_core_init
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
