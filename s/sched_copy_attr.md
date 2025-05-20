# Function: <code>sched_copy_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad9da)
Location: kernel/sched/core.c:4111
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b038a)
Location: kernel/sched/core.c:4361
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b651a)
Location: kernel/sched/core.c:4398
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b279a)
Location: kernel/sched/core.c:4298
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9b9a)
Location: kernel/sched/core.c:4342
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba580)
Location: kernel/sched/core.c:4477
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810ba580-ffffffff810ba657: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3740)
Location: kernel/sched/core.c:4462
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810c3740-ffffffff810c3817: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9780)
Location: kernel/sched/core.c:4899
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810c9780-ffffffff810c990d: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2850)
Location: kernel/sched/core.c:5119
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810d2850-ffffffff810d2a18: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de180)
Location: kernel/sched/core.c:5352
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810de180-ffffffff810de332: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dabe0)
Location: kernel/sched/core.c:6171
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810dabe0-ffffffff810dad92: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc730)
Location: kernel/sched/core.c:6472
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810dc730-ffffffff810dc8e1: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ee260)
Location: kernel/sched/core.c:7636
Inline: False
Direct callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff810ee260-ffffffff810ee411: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110bd40)
Location: kernel/sched/core.c:7744
Inline: False
Direct callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff8110bd40-ffffffff8110bef2: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811321c0)
Location: kernel/sched/core.c:7886
Inline: False
Direct callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff811321c0-ffffffff81132370: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81140430)
Location: kernel/sched/core.c:7995
Inline: False
Direct callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff81140430-ffffffff811405e5: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114b4e0)
Location: kernel/sched/core.c:8046
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff8114b4e0-ffffffff8114b695: sched_copy_attr (STB_LOCAL)
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
In kernel/sched/core.c (ffff800010137704)
Location: kernel/sched/core.c:5119
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setattr
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
In kernel/sched/core.c (c038c2e8)
Location: kernel/sched/core.c:5119
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
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
In kernel/sched/core.c (c000000000182d58)
Location: kernel/sched/core.c:5119
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
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
In kernel/sched/core.c (ffffffe0000eb984)
Location: kernel/sched/core.c:5119
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
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
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ccbd0)
Location: kernel/sched/core.c:5119
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810ccbd0-ffffffff810ccd98: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb3d0)
Location: kernel/sched/core.c:5119
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810bb3d0-ffffffff810bb598: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc0f0)
Location: kernel/sched/core.c:5119
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810cc0f0-ffffffff810cc2b8: sched_copy_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_copy_attr(struct sched_attr *uattr, struct sched_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4950)
Location: kernel/sched/core.c:5119
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810d4950-ffffffff810d4b18: sched_copy_attr (STB_LOCAL)
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
