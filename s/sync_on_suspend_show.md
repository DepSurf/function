# Function: <code>sync_on_suspend_show</code>

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
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112590)
Location: kernel/power/main.c:202
Inline: False
```
**Symbols:**

```
ffffffff81112590-ffffffff811125b6: sync_on_suspend_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110f660)
Location: kernel/power/main.c:202
Inline: False
```
**Symbols:**

```
ffffffff8110f660-ffffffff8110f686: sync_on_suspend_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81110100)
Location: kernel/power/main.c:202
Inline: False
```
**Symbols:**

```
ffffffff81110100-ffffffff81110126: sync_on_suspend_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:202
Inline: False
```
**Symbols:**

```
ffffffff81130320-ffffffff8113035f: sync_on_suspend_show (STB_LOCAL)
ffffffff81ca9729-ffffffff81ca9744: sync_on_suspend_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:205
Inline: False
```
**Symbols:**

```
ffffffff81151b30-ffffffff81151b78: sync_on_suspend_show (STB_LOCAL)
ffffffff81e59724-ffffffff81e5973f: sync_on_suspend_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:208
Inline: False
```
**Symbols:**

```
ffffffff81180860-ffffffff811808a8: sync_on_suspend_show (STB_LOCAL)
ffffffff82058335-ffffffff82058350: sync_on_suspend_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:249
Inline: False
```
**Symbols:**

```
ffffffff81191680-ffffffff811916c8: sync_on_suspend_show (STB_LOCAL)
ffffffff820d6c45-ffffffff820d6c60: sync_on_suspend_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t sync_on_suspend_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:233
Inline: False
```
**Symbols:**

```
ffffffff811a0040-ffffffff811a0088: sync_on_suspend_show (STB_LOCAL)
ffffffff821b1edb-ffffffff821b1ef6: sync_on_suspend_show.cold (STB_LOCAL)
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
