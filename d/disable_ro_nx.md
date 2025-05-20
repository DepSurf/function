# Function: <code>disable_ro_nx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105ef0)
Location: kernel/module.c:1958
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81105f40: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d820)
Location: kernel/module.c:1979
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8110d820-ffffffff8110d88e: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115120)
Location: kernel/module.c:1989
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81115120-ffffffff81115197: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116100)
Location: kernel/module.c:2016
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81116100-ffffffff81116177: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121680)
Location: kernel/module.c:2024
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81121680-ffffffff811216f7: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112f170)
Location: kernel/module.c:2023
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8112f170-ffffffff8112f1e9: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void disable_ro_nx(const struct module_layout *layout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113ab00)
Location: kernel/module.c:2024
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8113ab00-ffffffff8113ab79: disable_ro_nx (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
