# Function: <code>acpi_handle_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147ad2d)
Location: drivers/acpi/utils.c:476
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_handle_printk
  - drivers/acpi/utils.c:__acpi_handle_debug
```
**Symbols:**

```
ffffffff8147ad2d-ffffffff8147ad94: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c92da)
Location: drivers/acpi/utils.c:473
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff814c92da-ffffffff814c9341: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb21e)
Location: drivers/acpi/utils.c:473
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff814eb21e-ffffffff814eb285: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f7270)
Location: drivers/acpi/utils.c:473
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff814f7270-ffffffff814f72d7: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815380e0)
Location: drivers/acpi/utils.c:474
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815380e0-ffffffff81538147: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156dd60)
Location: drivers/acpi/utils.c:474
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff8156dd60-ffffffff8156ddc7: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81585920)
Location: drivers/acpi/utils.c:474
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff81585920-ffffffff81585987: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6590)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815b6590-ffffffff815b65f7: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d77c0)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815d77c0-ffffffff815d7827: acpi_handle_path (STB_LOCAL)
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
In drivers/acpi/utils.c (ffffffff81681a0c)
Location: drivers/acpi/utils.c:462
Inline: True
Inline callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8169fea0)
Location: drivers/acpi/utils.c:458
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff8169fea0-ffffffff8169ff07: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682d20)
Location: drivers/acpi/utils.c:438
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff81682d20-ffffffff81682d87: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7e70)
Location: drivers/acpi/utils.c:452
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff816f7e70-ffffffff816f7ed7: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81824e60)
Location: drivers/acpi/utils.c:452
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff81824e60-ffffffff81824ed1: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81955fe0)
Location: drivers/acpi/utils.c:490
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff81955fe0-ffffffff81956051: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c3e0)
Location: drivers/acpi/utils.c:490
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff8199c3e0-ffffffff8199c451: acpi_handle_path (STB_LOCAL)
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
In drivers/acpi/utils.c (ffffffff819e4a44)
Location: drivers/acpi/utils.c:562
Inline: True
Inline callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
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
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010765150)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffff800010765150-ffff8000107651d4: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815caf50)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815caf50-ffffffff815cafb7: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b3fa0)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815b3fa0-ffffffff815b4007: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cbaa0)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815cbaa0-ffffffff815cbb07: acpi_handle_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *acpi_handle_path(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e5940)
Location: drivers/acpi/utils.c:461
Inline: False
Direct callers:
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
```
**Symbols:**

```
ffffffff815e5940-ffffffff815e59a7: acpi_handle_path (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
