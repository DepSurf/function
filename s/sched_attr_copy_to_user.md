# Function: <code>sched_attr_copy_to_user</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb710)
Location: kernel/sched/core.c:5118
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810cb710-ffffffff810cb793: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3940)
Location: kernel/sched/core.c:5309
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810d3940-ffffffff810d39c3: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd950)
Location: kernel/sched/core.c:5542
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810dd950-ffffffff810dd9d1: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da860)
Location: kernel/sched/core.c:6361
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810da860-ffffffff810da8f8: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbf30)
Location: kernel/sched/core.c:6662
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810dbf30-ffffffff810dbfa8: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ef0a0)
Location: kernel/sched/core.c:7838
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810ef0a0-ffffffff810ef118: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110bf00)
Location: kernel/sched/core.c:7946
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff8110bf00-ffffffff8110bf9d: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112f9a0)
Location: kernel/sched/core.c:8088
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff8112f9a0-ffffffff8112fa3d: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d410)
Location: kernel/sched/core.c:8197
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff8113d410-ffffffff8113d4a7: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148580)
Location: kernel/sched/core.c:8234
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff81148580-ffffffff81148617: sched_attr_copy_to_user (STB_LOCAL)
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
In kernel/sched/core.c (ffff800010135038)
Location: kernel/sched/core.c:5309
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_getattr
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
In kernel/sched/core.c (c038c810)
Location: kernel/sched/core.c:5309
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
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
In kernel/sched/core.c (c00000000017da08)
Location: kernel/sched/core.c:5309
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
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
In kernel/sched/core.c (ffffffe0000ebd12)
Location: kernel/sched/core.c:5309
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
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
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cdc30)
Location: kernel/sched/core.c:5309
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810cdc30-ffffffff810cdcb3: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc4c0)
Location: kernel/sched/core.c:5309
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810bc4c0-ffffffff810bc543: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd0a0)
Location: kernel/sched/core.c:5309
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810cd0a0-ffffffff810cd123: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr *uattr, struct sched_attr *kattr, unsigned int usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d5a30)
Location: kernel/sched/core.c:5309
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810d5a30-ffffffff810d5ab3: sched_attr_copy_to_user (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
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
