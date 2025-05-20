# Function: <code>port_debugfs_show</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81667fb0)
Location: drivers/char/virtio_console.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81667fb0-ffffffff816680ab: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169da40)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffff8169da40-ffffffff8169db2e: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c07b0)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffff816c07b0-ffffffff816c089e: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817745c0)
Location: drivers/char/virtio_console.c:1297
Inline: False
```
**Symbols:**

```
ffffffff817745c0-ffffffff817746ae: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8178f320)
Location: drivers/char/virtio_console.c:1297
Inline: False
```
**Symbols:**

```
ffffffff8178f320-ffffffff8178f40e: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81772130)
Location: drivers/char/virtio_console.c:1297
Inline: False
```
**Symbols:**

```
ffffffff81772130-ffffffff8177221e: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1297
Inline: False
```
**Symbols:**

```
ffffffff817f8080-ffffffff817f819a: port_debugfs_show (STB_LOCAL)
ffffffff81cfaafd-ffffffff81cfab4e: port_debugfs_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1298
Inline: False
```
**Symbols:**

```
ffffffff81936350-ffffffff81936481: port_debugfs_show (STB_LOCAL)
ffffffff81ec3238-ffffffff81ec3289: port_debugfs_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1293
Inline: False
```
**Symbols:**

```
ffffffff81a96180-ffffffff81a962b1: port_debugfs_show (STB_LOCAL)
ffffffff82096516-ffffffff82096567: port_debugfs_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1294
Inline: False
```
**Symbols:**

```
ffffffff81ae1990-ffffffff81ae1ac1: port_debugfs_show (STB_LOCAL)
ffffffff8211745e-ffffffff821174af: port_debugfs_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (0)
Location: drivers/char/virtio_console.c:1262
Inline: False
```
**Symbols:**

```
ffffffff81b34d80-ffffffff81b34eb1: port_debugfs_show (STB_LOCAL)
ffffffff821f51d3-ffffffff821f5224: port_debugfs_show.cold (STB_LOCAL)
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
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b2888)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffff8000108b2888-ffff8000108b2990: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ad3fc)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
c09ad3fc-c09ad4f8: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094b8b0)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
c00000000094b8b0-c00000000094b9fc: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe000564d14)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffe000564d14-ffffffe000564e22: port_debugfs_show (STB_LOCAL)
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
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81686200)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffff81686200-ffffffff816862ee: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81663ea0)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffff81663ea0-ffffffff81663f8e: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b45f0)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffff816b45f0-ffffffff816b46de: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int port_debugfs_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816ceb50)
Location: drivers/char/virtio_console.c:1299
Inline: False
```
**Symbols:**

```
ffffffff816ceb50-ffffffff816cec3e: port_debugfs_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
