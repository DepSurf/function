# Function: <code>request_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130fa80)
Location: fs/fuse/dev.c:386
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8130fa80-ffffffff8130fc4f: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813435e0)
Location: fs/fuse/dev.c:366
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff813435e0-ffffffff813437ae: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81359bf0)
Location: fs/fuse/dev.c:366
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81359bf0-ffffffff81359dbe: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136e3c0)
Location: fs/fuse/dev.c:366
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8136e3c0-ffffffff8136e57f: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81392fd0)
Location: fs/fuse/dev.c:366
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81392fd0-ffffffff81393197: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c17c0)
Location: fs/fuse/dev.c:379
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff813c17c0-ffffffff813c197a: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dae90)
Location: fs/fuse/dev.c:428
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff813dae90-ffffffff813db05e: request_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void request_end(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:430
Inline: False
Direct callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81406a70-ffffffff81406c33: request_end (STB_LOCAL)
ffffffff8140952f-ffffffff81409555: request_end.cold (STB_LOCAL)
```
</details>
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
</ul>
