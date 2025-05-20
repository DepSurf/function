# Function: <code>frob_rodata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105e50)
Location: kernel/module.c:1873
Inline: True
Direct callers:
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_enable_ro
  - kernel/module.c:module_enable_ro
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81105e50-ffffffff81105e92: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d730)
Location: kernel/module.c:1878
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:module_enable_ro
  - kernel/module.c:module_enable_ro
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff8110d730-ffffffff8110d775: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115030)
Location: kernel/module.c:1870
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81115030-ffffffff81115075: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811152b0)
Location: kernel/module.c:1897
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff811152b0-ffffffff811152f5: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120860)
Location: kernel/module.c:1905
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81120860-ffffffff811208a7: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e290)
Location: kernel/module.c:1904
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff8112e290-ffffffff8112e2d7: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139b90)
Location: kernel/module.c:1905
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81139b90-ffffffff81139bd7: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145270)
Location: kernel/module.c:1913
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81145270-ffffffff811452b5: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150d80)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81150d80-ffffffff81150dc5: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811612c0)
Location: kernel/module.c:2008
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff811612c0-ffffffff81161305: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115d200)
Location: kernel/module.c:2067
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff8115d200-ffffffff8115d245: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e2f0)
Location: kernel/module.c:1977
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff8115e2f0-ffffffff8115e335: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81183530)
Location: kernel/module.c:1979
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff81183530-ffffffff81183575: frob_rodata (STB_LOCAL)
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
In kernel/module/strict_rwx.c (ffffffff81190743)
Location: kernel/module/strict_rwx.c:42
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
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
In kernel/module/strict_rwx.c (ffffffff811cdc43)
Location: kernel/module/strict_rwx.c:42
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bfba0)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffff8000101bfba0-ffff8000101bfc0c: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0407320)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
c0407320-c0407388: frob_rodata (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811493a0)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff811493a0-ffffffff811493e5: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c650)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff8113c650-ffffffff8113c695: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147250)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81147250-ffffffff81147295: frob_rodata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153e60)
Location: kernel/module.c:1970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81153e60-ffffffff81153ea5: frob_rodata (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
