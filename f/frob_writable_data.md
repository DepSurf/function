# Function: <code>frob_writable_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105ea0)
Location: kernel/module.c:1883
Inline: True
Direct callers:
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81105ea0-ffffffff81105ee2: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d7d0)
Location: kernel/module.c:1898
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff8110d7d0-ffffffff8110d815: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811150d0)
Location: kernel/module.c:1890
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff811150d0-ffffffff81115115: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115350)
Location: kernel/module.c:1917
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81115350-ffffffff81115395: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120900)
Location: kernel/module.c:1925
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81120900-ffffffff81120947: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e330)
Location: kernel/module.c:1924
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff8112e330-ffffffff8112e377: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void frob_writable_data(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139c30)
Location: kernel/module.c:1925
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81139c30-ffffffff81139c77: frob_writable_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81146720)
Location: kernel/module.c:1933
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81146720-ffffffff8114675f: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81152300)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81152300-ffffffff8115233f: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81161df0)
Location: kernel/module.c:2028
Inline: True
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff81161df0-ffffffff81161e2f: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8115df10)
Location: kernel/module.c:2087
Inline: True
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff8115df10-ffffffff8115df4f: frob_writable_data.constprop.0 (STB_LOCAL)
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
In kernel/module.c (ffffffff8115ef40)
Location: kernel/module.c:1997
Inline: True
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff8115ef40-ffffffff8115ef7f: frob_writable_data.constprop.0 (STB_LOCAL)
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
In kernel/module.c (ffffffff81184290)
Location: kernel/module.c:1999
Inline: True
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff81184290-ffffffff811842cf: frob_writable_data.constprop.0 (STB_LOCAL)
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
In kernel/module/strict_rwx.c (ffffffff8119077d)
Location: kernel/module/strict_rwx.c:56
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
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
In kernel/module/strict_rwx.c (ffffffff811cdc7d)
Location: kernel/module/strict_rwx.c:56
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffff8000101c0fc0)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffff8000101c0fc0-ffff8000101c1028: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (c0408664)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
c0408664-c04086c8: frob_writable_data.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8114a920)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114a920-ffffffff8114a95f: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8113dbd0)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113dbd0-ffffffff8113dc0f: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811487d0)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811487d0-ffffffff8114880f: frob_writable_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81155440)
Location: kernel/module.c:1990
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81155440-ffffffff8115547f: frob_writable_data.constprop.0 (STB_LOCAL)
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
</ul>
