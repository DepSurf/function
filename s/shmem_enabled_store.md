# Function: <code>shmem_enabled_store</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811beb10)
Location: mm/shmem.c:3974
Inline: False
```
**Symbols:**

```
ffffffff811beb10-ffffffff811bebd9: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cf360)
Location: mm/shmem.c:3868
Inline: False
```
**Symbols:**

```
ffffffff811cf360-ffffffff811cf426: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d7a20)
Location: mm/shmem.c:4033
Inline: False
```
**Symbols:**

```
ffffffff811d7a20-ffffffff811d7af3: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ec8a0)
Location: mm/shmem.c:4078
Inline: False
```
**Symbols:**

```
ffffffff811ec8a0-ffffffff811ec973: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3794
Inline: False
```
**Symbols:**

```
ffffffff8120dea0-ffffffff8120df67: shmem_enabled_store (STB_LOCAL)
ffffffff812140ac-ffffffff812140b8: shmem_enabled_store.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3780
Inline: False
```
**Symbols:**

```
ffffffff81220a40-ffffffff81220b07: shmem_enabled_store (STB_LOCAL)
ffffffff81226f7f-ffffffff81226f8b: shmem_enabled_store.cold.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3857
Inline: False
```
**Symbols:**

```
ffffffff812301e0-ffffffff812302a7: shmem_enabled_store (STB_LOCAL)
ffffffff81236aff-ffffffff81236b0b: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
ffffffff8123e500-ffffffff8123e6e9: shmem_enabled_store (STB_LOCAL)
ffffffff81244d3f-ffffffff81244d4b: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3941
Inline: False
```
**Symbols:**

```
ffffffff8126b940-ffffffff8126ba06: shmem_enabled_store (STB_LOCAL)
ffffffff812729e6-ffffffff812729f2: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:4048
Inline: False
```
**Symbols:**

```
ffffffff81276300-ffffffff812763c6: shmem_enabled_store (STB_LOCAL)
ffffffff81be6ebd-ffffffff81be6ec9: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3993
Inline: False
```
**Symbols:**

```
ffffffff8127b630-ffffffff8127b7fc: shmem_enabled_store (STB_LOCAL)
ffffffff81bd8c29-ffffffff81bd8c35: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3965
Inline: False
```
**Symbols:**

```
ffffffff812b94e0-ffffffff812b9724: shmem_enabled_store (STB_LOCAL)
ffffffff81cba8f3-ffffffff81cba8ff: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3981
Inline: False
```
**Symbols:**

```
ffffffff813153b0-ffffffff81315617: shmem_enabled_store (STB_LOCAL)
ffffffff81e6c1f0-ffffffff81e6c1fc: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813892b0)
Location: mm/shmem.c:4109
Inline: False
```
**Symbols:**

```
ffffffff813892b0-ffffffff81389523: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bb560)
Location: mm/shmem.c:4315
Inline: False
```
**Symbols:**

```
ffffffff813bb560-ffffffff813bb7d3: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e6080)
Location: mm/shmem.c:4683
Inline: False
```
**Symbols:**

```
ffffffff813e6080-ffffffff813e62f3: shmem_enabled_store (STB_LOCAL)
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
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d00e8)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
ffff8000102d00e8-ffff8000102d0310: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038e540)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
c00000000038e540-c00000000038e8a4: shmem_enabled_store (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
ffffffff81236b50-ffffffff81236d39: shmem_enabled_store (STB_LOCAL)
ffffffff8123d38f-ffffffff8123d39b: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
ffffffff81229bb0-ffffffff81229d99: shmem_enabled_store (STB_LOCAL)
ffffffff8123038f-ffffffff8123039b: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
ffffffff812348f0-ffffffff81234ad9: shmem_enabled_store (STB_LOCAL)
ffffffff8123b12f-ffffffff8123b13b: shmem_enabled_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t shmem_enabled_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:3978
Inline: False
```
**Symbols:**

```
ffffffff81244a50-ffffffff81244c39: shmem_enabled_store (STB_LOCAL)
ffffffff8124a83f-ffffffff8124a84b: shmem_enabled_store.cold (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
