# Function: <code>io_notif_complete_tw_ext</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void io_notif_complete_tw_ext(struct io_kiocb *notif, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/notif.c (0)
Location: io_uring/notif.c:12
Inline: False
```
**Symbols:**

```
ffffffff817a5020-ffffffff817a50c4: io_notif_complete_tw_ext (STB_LOCAL)
ffffffff82077a42-ffffffff82077a81: io_notif_complete_tw_ext.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void io_notif_complete_tw_ext(struct io_kiocb *notif, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/notif.c (0)
Location: io_uring/notif.c:12
Inline: False
```
**Symbols:**

```
ffffffff817e5ff0-ffffffff817e6094: io_notif_complete_tw_ext (STB_LOCAL)
ffffffff820f7b1c-ffffffff820f7b5b: io_notif_complete_tw_ext.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_notif_complete_tw_ext(struct io_kiocb *notif, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/notif.c (0)
Location: io_uring/notif.c:12
Inline: False
```
**Symbols:**

```
ffffffff8182a210-ffffffff8182a2b4: io_notif_complete_tw_ext (STB_LOCAL)
ffffffff821d54b5-ffffffff821d54f4: io_notif_complete_tw_ext.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_tw_state *ts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
