# Function: <code>__nvm_find_target_type</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81679ef0)
Location: drivers/lightnvm/core.c:253
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
```
**Symbols:**

```
ffffffff81679ef0-ffffffff81679f45: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81698ac0)
Location: drivers/lightnvm/core.c:253
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
```
**Symbols:**

```
ffffffff81698ac0-ffffffff81698b15: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d15f0)
Location: drivers/lightnvm/core.c:241
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816d15f0-ffffffff816d1648: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f5410)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816f5410-ffffffff816f5468: __nvm_find_target_type (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817ae79a)
Location: drivers/lightnvm/core.c:243
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff817c331a)
Location: drivers/lightnvm/core.c:239
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff817a66ba)
Location: drivers/lightnvm/core.c:239
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108dea80)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffff8000108dea80-ffff8000108deb04: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cdb10)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
c09cdb10-c09cdb7c: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c0000000009723f0)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
c0000000009723f0-c000000000972640: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000574cde)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffe000574cde-ffffffe000574d48: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bac00)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816bac00-ffffffff816bac58: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e90d0)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816e90d0-ffffffff816e9128: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nvm_tgt_type *__nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81703910)
Location: drivers/lightnvm/core.c:243
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff81703910-ffffffff81703968: __nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
