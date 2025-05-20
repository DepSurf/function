# Function: <code>__percpu_init_rwsem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *brw, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ca000)
Location: kernel/locking/percpu-rwsem.c:11
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff810ca000-ffffffff810ca07a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *brw, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ce990)
Location: kernel/locking/percpu-rwsem.c:11
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810ce990-ffffffff810cea0a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d55d0)
Location: kernel/locking/percpu-rwsem.c:11
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810d55d0-ffffffff810d564d: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d45a0)
Location: kernel/locking/percpu-rwsem.c:10
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810d45a0-ffffffff810d460b: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810dc500)
Location: kernel/locking/percpu-rwsem.c:10
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810dc500-ffffffff810dc56b: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810e4b50)
Location: kernel/locking/percpu-rwsem.c:10
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810e4b50-ffffffff810e4bbb: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f0130)
Location: kernel/locking/percpu-rwsem.c:10
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/events/uprobes.c:init_uprobes
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810f0130-ffffffff810f019b: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f87a0)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810f87a0-ffffffff810f880a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff811045e0)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff811045e0-ffffffff8110464a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110f100)
Location: kernel/locking/percpu-rwsem.c:12
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8110f100-ffffffff8110f166: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110c2c0)
Location: kernel/locking/percpu-rwsem.c:12
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8110c2c0-ffffffff8110c326: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110e100)
Location: kernel/locking/percpu-rwsem.c:12
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8110e100-ffffffff8110e166: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8112d850)
Location: kernel/locking/percpu-rwsem.c:12
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8112d850-ffffffff8112d8b6: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8114e860)
Location: kernel/locking/percpu-rwsem.c:14
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff8114e860-ffffffff8114e8da: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8117d900)
Location: kernel/locking/percpu-rwsem.c:14
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff8117d900-ffffffff8117d97a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8118e5a0)
Location: kernel/locking/percpu-rwsem.c:14
Inline: False
Direct callers:
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_percpu_param_init
```
**Symbols:**

```
ffffffff8118e5a0-ffffffff8118e61a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8119cf50)
Location: kernel/locking/percpu-rwsem.c:14
Inline: False
Direct callers:
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_percpu_param_init
```
**Symbols:**

```
ffffffff8119cf50-ffffffff8119cfca: __percpu_init_rwsem (STB_GLOBAL)
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
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffff80001016a230)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff80001016a230-ffff80001016a2b0: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c03b622c)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c03b622c-c03b6298: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c0000000001c1df0)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0000000001c1df0-c0000000001c1eb0: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffe00010b0a2)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe00010b0a2-ffffffe00010b112: __percpu_init_rwsem (STB_GLOBAL)
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
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fd8f0)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810fd8f0-ffffffff810fd95a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810edaf0)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810edaf0-ffffffff810edb5a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810faab0)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff810faab0-ffffffff810fab1a: __percpu_init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore *sem, const char *name, struct lock_class_key *rwsem_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81105c80)
Location: kernel/locking/percpu-rwsem.c:13
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - fs/super.c:alloc_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81105c80-ffffffff81105cea: __percpu_init_rwsem (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct percpu_rw_semaphore *sem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_rw_semaphore *brw</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lock_class_key *key</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lock_class_key *rwsem_key</code>
</li>
</ul>
</details>
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
