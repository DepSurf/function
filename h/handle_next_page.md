# Function: <code>handle_next_page</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void *handle_next_page(struct squashfs_page_actor *actor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/page_actor.c (ffffffff815f1ee0)
Location: fs/squashfs/page_actor.c:63
Inline: False
Direct callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
**Symbols:**

```
ffffffff815f1ee0-ffffffff815f1fbb: handle_next_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *handle_next_page(struct squashfs_page_actor *actor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/page_actor.c (ffffffff81629fd0)
Location: fs/squashfs/page_actor.c:63
Inline: False
Direct callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
**Symbols:**

```
ffffffff81629fd0-ffffffff8162a0ab: handle_next_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *handle_next_page(struct squashfs_page_actor *actor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/page_actor.c (ffffffff81663250)
Location: fs/squashfs/page_actor.c:63
Inline: False
Direct callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
**Symbols:**

```
ffffffff81663250-ffffffff8166332b: handle_next_page (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
