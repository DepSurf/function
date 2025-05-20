# Function: <code>sync_on_suspend_store</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112810)
Location: kernel/power/main.c:208
Inline: False
```
**Symbols:**

```
ffffffff81112810-ffffffff81112882: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110f8e0)
Location: kernel/power/main.c:208
Inline: False
```
**Symbols:**

```
ffffffff8110f8e0-ffffffff8110f952: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81110380)
Location: kernel/power/main.c:208
Inline: False
```
**Symbols:**

```
ffffffff81110380-ffffffff811103f2: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8112fd30)
Location: kernel/power/main.c:208
Inline: False
```
**Symbols:**

```
ffffffff8112fd30-ffffffff8112fda2: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811513a0)
Location: kernel/power/main.c:211
Inline: False
```
**Symbols:**

```
ffffffff811513a0-ffffffff81151426: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8117ff60)
Location: kernel/power/main.c:214
Inline: False
```
**Symbols:**

```
ffffffff8117ff60-ffffffff8117ffe6: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81190d30)
Location: kernel/power/main.c:255
Inline: False
```
**Symbols:**

```
ffffffff81190d30-ffffffff81190db6: sync_on_suspend_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sync_on_suspend_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119f6f0)
Location: kernel/power/main.c:239
Inline: False
```
**Symbols:**

```
ffffffff8119f6f0-ffffffff8119f776: sync_on_suspend_store (STB_LOCAL)
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
