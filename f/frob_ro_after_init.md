# Function: <code>frob_ro_after_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d780)
Location: kernel/module.c:1888
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:module_enable_ro
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff8110d780-ffffffff8110d7c5: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115080)
Location: kernel/module.c:1880
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81115080-ffffffff811150c5: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115300)
Location: kernel/module.c:1907
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81115300-ffffffff81115345: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811208b0)
Location: kernel/module.c:1915
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff811208b0-ffffffff811208f7: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e2e0)
Location: kernel/module.c:1914
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff8112e2e0-ffffffff8112e327: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139be0)
Location: kernel/module.c:1915
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:disable_ro_nx
  - kernel/module.c:disable_ro_nx
```
**Symbols:**

```
ffffffff81139be0-ffffffff81139c27: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145220)
Location: kernel/module.c:1923
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81145220-ffffffff81145265: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150d30)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81150d30-ffffffff81150d75: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161310)
Location: kernel/module.c:2018
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff81161310-ffffffff81161355: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115d250)
Location: kernel/module.c:2077
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff8115d250-ffffffff8115d295: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e340)
Location: kernel/module.c:1987
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff8115e340-ffffffff8115e385: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81183580)
Location: kernel/module.c:1989
Inline: False
Direct callers:
  - kernel/module.c:complete_formation
```
**Symbols:**

```
ffffffff81183580-ffffffff811835c5: frob_ro_after_init (STB_LOCAL)
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
In kernel/module/strict_rwx.c (ffffffff81190760)
Location: kernel/module/strict_rwx.c:49
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
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
In kernel/module/strict_rwx.c (ffffffff811cdc60)
Location: kernel/module/strict_rwx.c:49
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
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
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bfb30)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffff8000101bfb30-ffff8000101bfb9c: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c04072b8)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
c04072b8-c0407320: frob_ro_after_init (STB_LOCAL)
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
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149350)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81149350-ffffffff81149395: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c600)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff8113c600-ffffffff8113c645: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147200)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81147200-ffffffff81147245: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void frob_ro_after_init(const struct module_layout *layout, int (*set_memory)(long unsigned int, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153e10)
Location: kernel/module.c:1980
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:module_disable_ro
```
**Symbols:**

```
ffffffff81153e10-ffffffff81153e55: frob_ro_after_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
