# Function: <code>cec_receive_msg</code>

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
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff81807880)
Location: drivers/media/cec/cec-api.c:227
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81807880-ffffffff81807ade: cec_receive_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff818491c0)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff818491c0-ffffffff81849415: cec_receive_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff8187a9c0)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8187a9c0-ffffffff8187ac15: cec_receive_msg (STB_LOCAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffff800010ac2388)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010ac2388-ffff800010ac25d4: cec_receive_msg (STB_LOCAL)
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
In drivers/media/cec/cec-api.c (0)
Location: drivers/media/cec/cec-api.c:219
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (c000000000ba4a50)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000ba4a50-c000000000ba4d90: cec_receive_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffe0006c33c8)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c33c8-ffffffe0006c35a2: cec_receive_msg (STB_LOCAL)
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
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff81822f30)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81822f30-ffffffff81823185: cec_receive_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff817ea5d0)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817ea5d0-ffffffff817ea825: cec_receive_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff8186fe70)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186fe70-ffffffff818700c5: cec_receive_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cec_receive_msg(struct cec_fh *fh, struct cec_msg *msg, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-api.c (ffffffff81889df0)
Location: drivers/media/cec/cec-api.c:219
Inline: False
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81889df0-ffffffff8188a036: cec_receive_msg (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
