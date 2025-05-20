# Function: <code>scsi_req_init</code>

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
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814430c0)
Location: block/scsi_ioctl.c:762
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_init_rq
  - drivers/scsi/scsi_lib.c:scsi_initialize_rq
```
**Symbols:**

```
ffffffff814430c0-ffffffff814430ee: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8146fb50)
Location: block/scsi_ioctl.c:762
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_initialize_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff8146fb50-ffffffff8146fb7e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814a3ec0)
Location: block/scsi_ioctl.c:720
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff814a3ec0-ffffffff814a3eee: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814be930)
Location: block/scsi_ioctl.c:720
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff814be930-ffffffff814be95e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ed1e0)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff814ed1e0-ffffffff814ed20e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81506620)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81506620-ffffffff8150664e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81566f80)
Location: block/scsi_ioctl.c:886
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81566f80-ffffffff81566fae: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81581e10)
Location: block/scsi_ioctl.c:877
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81581e10-ffffffff81581e3e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81588c10)
Location: block/scsi_ioctl.c:873
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81588c10-ffffffff81588c3e: scsi_req_init (STB_GLOBAL)
```
</details>
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
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff800010607958)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffff800010607958-ffff800010607990: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c07b3ac8)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
c07b3ac8-c07b3b04: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a46a0)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
c0000000007a46a0-c0000000007a46c8: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffe000442460)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffe000442460-ffffffe00044249a: scsi_req_init (STB_GLOBAL)
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
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fec00)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff814fec00-ffffffff814fec2e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ef110)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff814ef110-ffffffff814ef13e: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fac90)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff814fac90-ffffffff814facbe: scsi_req_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_req_init(struct scsi_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81513d40)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81513d40-ffffffff81513d6e: scsi_req_init (STB_GLOBAL)
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
