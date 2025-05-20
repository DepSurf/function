# Function: <code>fail_last_dev_store</code>

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
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818900f0)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffffffff818900f0-ffffffff8189016f: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8195ef10)
Location: drivers/md/md.c:5401
Inline: False
```
**Symbols:**

```
ffffffff8195ef10-ffffffff8195ef8f: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819657e0)
Location: drivers/md/md.c:5430
Inline: False
```
**Symbols:**

```
ffffffff819657e0-ffffffff8196585f: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819499e0)
Location: drivers/md/md.c:5394
Inline: False
```
**Symbols:**

```
ffffffff819499e0-ffffffff81949a5f: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5413
Inline: False
```
**Symbols:**

```
ffffffff819f1280-ffffffff819f1323: fail_last_dev_store (STB_LOCAL)
ffffffff81d277b1-ffffffff81d277f0: fail_last_dev_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5402
Inline: False
```
**Symbols:**

```
ffffffff81b5abc0-ffffffff81b5ac71: fail_last_dev_store (STB_LOCAL)
ffffffff81ef3630-ffffffff81ef366f: fail_last_dev_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5377
Inline: False
```
**Symbols:**

```
ffffffff81cf43e0-ffffffff81cf4491: fail_last_dev_store (STB_LOCAL)
ffffffff820a7d86-ffffffff820a7dc5: fail_last_dev_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5360
Inline: False
```
**Symbols:**

```
ffffffff81d5c230-ffffffff81d5c2e1: fail_last_dev_store (STB_LOCAL)
ffffffff82129164-ffffffff821291a3: fail_last_dev_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5523
Inline: False
```
**Symbols:**

```
ffffffff81e13390-ffffffff81e13441: fail_last_dev_store (STB_LOCAL)
ffffffff8220ab4d-ffffffff8220ab8c: fail_last_dev_store.cold (STB_LOCAL)
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
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae2308)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffff800010ae2308-ffff800010ae2398: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc39a0)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
c0bc39a0-c0bc3a28: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bc9e00)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
c000000000bc9e00-c000000000bc9ec0: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006d8de2)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffffffe0006d8de2-ffffffe0006d8e40: fail_last_dev_store (STB_LOCAL)
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
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81835f70)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffffffff81835f70-ffffffff81835fef: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817fd5e0)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffffffff817fd5e0-ffffffff817fd65f: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818855a0)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffffffff818855a0-ffffffff8188561f: fail_last_dev_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fail_last_dev_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a1320)
Location: drivers/md/md.c:5262
Inline: False
```
**Symbols:**

```
ffffffff818a1320-ffffffff818a139f: fail_last_dev_store (STB_LOCAL)
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
