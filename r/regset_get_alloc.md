# Function: <code>regset_get_alloc</code>

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
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff810d5156)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff810d50f0-ffffffff810d5107: regset_get_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff810d6e36)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff810d6dd0-ffffffff810d6de7: regset_get_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff810ea6d6)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff810ea670-ffffffff810ea687: regset_get_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff81105455)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff811053e0-ffffffff81105403: regset_get_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff8112aef5)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff8112ae70-ffffffff8112ae93: regset_get_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff81138165)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff811380e0-ffffffff81138103: regset_get_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regset_get_alloc(struct task_struct *target, const struct user_regset *regset, unsigned int size, void **data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/regset.c (ffffffff81143375)
Location: kernel/regset.c:42
Inline: True
Inline callers:
  - kernel/regset.c:copy_regset_to_user
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff811432f0-ffffffff81143313: regset_get_alloc (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
