# Function: <code>ipc_get_maxid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipc_get_maxid(struct ipc_ids *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813249c0)
Location: ipc/util.c:183
Inline: False
```
**Symbols:**

```
ffffffff813249c0-ffffffff81324a59: ipc_get_maxid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipc_get_maxid(struct ipc_ids *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813595c0)
Location: ipc/util.c:183
Inline: False
```
**Symbols:**

```
ffffffff813595c0-ffffffff81359654: ipc_get_maxid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipc_get_maxid(struct ipc_ids *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8136faa0)
Location: ipc/util.c:183
Inline: False
```
**Symbols:**

```
ffffffff8136faa0-ffffffff8136fb37: ipc_get_maxid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipc_get_maxid(struct ipc_ids *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81382fa0)
Location: ipc/util.c:183
Inline: False
```
**Symbols:**

```
ffffffff81382fa0-ffffffff8138302a: ipc_get_maxid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a950e)
Location: ipc/util.h:118
Inline: True
```
```
In ipc/sem.c (ffffffff813aa5ee)
Location: ipc/util.h:118
Inline: True
```
```
In ipc/shm.c (ffffffff813ae80c)
Location: ipc/util.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d7a4a)
Location: ipc/util.h:121
Inline: True
```
```
In ipc/sem.c (ffffffff813d949e)
Location: ipc/util.h:121
Inline: True
```
```
In ipc/shm.c (ffffffff813dda9c)
Location: ipc/util.h:121
Inline: True
```
</details>
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
</ul>
