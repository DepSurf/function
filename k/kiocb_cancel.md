# Function: <code>kiocb_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kiocb_cancel(struct aio_kiocb *kiocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125b310)
Location: fs/aio.c:550
Inline: False
Direct callers:
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:SyS_io_cancel
```
**Symbols:**

```
ffffffff8125b310-ffffffff8125b34b: kiocb_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kiocb_cancel(struct aio_kiocb *kiocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81283ef0)
Location: fs/aio.c:560
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:free_ioctx_users
```
**Symbols:**

```
ffffffff81283ef0-ffffffff81283f2b: kiocb_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kiocb_cancel(struct aio_kiocb *kiocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297b60)
Location: fs/aio.c:563
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:free_ioctx_users
```
**Symbols:**

```
ffffffff81297b60-ffffffff81297b9b: kiocb_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kiocb_cancel(struct aio_kiocb *kiocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a5990)
Location: fs/aio.c:562
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:free_ioctx_users
```
**Symbols:**

```
ffffffff812a5990-ffffffff812a59cb: kiocb_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kiocb_cancel(struct aio_kiocb *kiocb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c8ea0)
Location: fs/aio.c:571
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:free_ioctx_users
```
**Symbols:**

```
ffffffff812c8ea0-ffffffff812c8eef: kiocb_cancel (STB_LOCAL)
```
</details>
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
</ul>
