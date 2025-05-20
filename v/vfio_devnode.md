# Function: <code>vfio_devnode</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0960)
Location: drivers/vfio/vfio.c:2188
Inline: False
```
**Symbols:**

```
ffffffff817d0960-ffffffff817d0988: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b3a0)
Location: drivers/vfio/vfio.c:2352
Inline: False
```
**Symbols:**

```
ffffffff8189b3a0-ffffffff8189b3c8: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9fb0)
Location: drivers/vfio/vfio.c:2376
Inline: False
```
**Symbols:**

```
ffffffff818a9fb0-ffffffff818a9fd8: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d350)
Location: drivers/vfio/vfio.c:2275
Inline: False
```
**Symbols:**

```
ffffffff8188d350-ffffffff8188d378: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920480)
Location: drivers/vfio/vfio.c:2382
Inline: False
```
**Symbols:**

```
ffffffff81920480-ffffffff819204a8: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a764a0)
Location: drivers/vfio/vfio.c:2120
Inline: False
```
**Symbols:**

```
ffffffff81a764a0-ffffffff81a764d2: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab01a0)
Location: drivers/vfio/vfio.c:2188
Inline: False
```
**Symbols:**

```
c000000000ab01a0-c000000000ab01f0: vfio_devnode (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177aa10)
Location: drivers/vfio/vfio.c:2188
Inline: False
```
**Symbols:**

```
ffffffff8177aa10-ffffffff8177aa38: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c57e0)
Location: drivers/vfio/vfio.c:2188
Inline: False
```
**Symbols:**

```
ffffffff817c57e0-ffffffff817c5808: vfio_devnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *vfio_devnode(struct device *dev, umode_t *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817dfa80)
Location: drivers/vfio/vfio.c:2188
Inline: False
```
**Symbols:**

```
ffffffff817dfa80-ffffffff817dfaa8: vfio_devnode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
