# Function: <code>mod_find_symname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int mod_find_symname(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81104ec0)
Location: kernel/module.c:3805
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81104ec0-ffffffff81104f2f: mod_find_symname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int mod_find_symname(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110c790)
Location: kernel/module.c:3976
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff8110c790-ffffffff8110c7ff: mod_find_symname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int mod_find_symname(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811141e0)
Location: kernel/module.c:3993
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff811141e0-ffffffff8111424f: mod_find_symname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int mod_find_symname(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114fe0)
Location: kernel/module.c:4038
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81114fe0-ffffffff8111504f: mod_find_symname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int mod_find_symname(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120580)
Location: kernel/module.c:4060
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81120580-ffffffff811205ef: mod_find_symname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mod_find_symname(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e040)
Location: kernel/module.c:4093
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff8112e040-ffffffff8112e0b0: mod_find_symname (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
</ul>
