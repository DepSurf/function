# Function: <code>sel_write_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sel_write_disable(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8134ab90)
Location: security/selinux/selinuxfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff8134ab90-ffffffff8134accc: sel_write_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sel_write_disable(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813806f0)
Location: security/selinux/selinuxfs.c:268
Inline: False
```
**Symbols:**

```
ffffffff813806f0-ffffffff81380807: sel_write_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sel_write_disable(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81397170)
Location: security/selinux/selinuxfs.c:270
Inline: False
```
**Symbols:**

```
ffffffff81397170-ffffffff81397287: sel_write_disable (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sel_write_disable(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b4590)
Location: security/selinux/selinuxfs.c:270
Inline: False
```
**Symbols:**

```
ffffffff816b4590-ffffffff816b4676: sel_write_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sel_write_disable(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f10f0)
Location: security/selinux/selinuxfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff816f10f0-ffffffff816f11d6: sel_write_disable (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
