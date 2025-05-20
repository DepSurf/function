# Function: <code>bpf_obj_get_next_id</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811917a0)
Location: kernel/bpf/syscall.c:1159
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811917a0-ffffffff81191868: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e770)
Location: kernel/bpf/syscall.c:1458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119e770-ffffffff8119e838: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3470)
Location: kernel/bpf/syscall.c:1696
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
```
**Symbols:**

```
ffffffff811b3470-ffffffff811b3536: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1bf0)
Location: kernel/bpf/syscall.c:1898
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c1bf0-ffffffff811c1cb6: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2240)
Location: kernel/bpf/syscall.c:2105
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d2240-ffffffff811d2306: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de7e0)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811de7e0-ffffffff811de8a6: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbae0)
Location: kernel/bpf/syscall.c:2991
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fbae0-ffffffff811fbba4: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811faba0)
Location: kernel/bpf/syscall.c:3135
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811faba0-ffffffff811fac66: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbb00)
Location: kernel/bpf/syscall.c:3158
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fbb00-ffffffff811fbbc6: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122d280)
Location: kernel/bpf/syscall.c:3341
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8122d280-ffffffff8122d346: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f7a0)
Location: kernel/bpf/syscall.c:3599
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8126f7a0-ffffffff8126f872: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c50a0)
Location: kernel/bpf/syscall.c:3642
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812c50a0-ffffffff812c5172: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ec1e0)
Location: kernel/bpf/syscall.c:3778
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812ec1e0-ffffffff812ec2b2: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130a780)
Location: kernel/bpf/syscall.c:4115
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8130a780-ffffffff8130a852: bpf_obj_get_next_id (STB_LOCAL)
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
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010260490)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff800010260490-ffff80001026071c: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c049316c)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c049316c-c0493288: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003050e0)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c0000000003050e0-c000000000305290: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019da16)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe00019da16-ffffffe00019db12: bpf_obj_get_next_id (STB_LOCAL)
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
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6e00)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d6e00-ffffffff811d6ec6: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9bc0)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c9bc0-ffffffff811c9c86: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4bd0)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d4bd0-ffffffff811d4c96: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_obj_get_next_id(const union bpf_attr *attr, union bpf_attr *uattr, struct idr *idr, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e2f00)
Location: kernel/bpf/syscall.c:2128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e2f00-ffffffff811e2fc6: bpf_obj_get_next_id (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
