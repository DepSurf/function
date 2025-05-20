# Function: <code>try_to_unlazy</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c5a0)
Location: fs/namei.c:682
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8132c5a0-ffffffff8132c62a: try_to_unlazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813330c0)
Location: fs/namei.c:741
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff813330c0-ffffffff8133314a: try_to_unlazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813809f0)
Location: fs/namei.c:768
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff813809f0-ffffffff81380a7a: try_to_unlazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81400d80)
Location: fs/namei.c:762
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff81400d80-ffffffff81400e46: try_to_unlazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148adf0)
Location: fs/namei.c:768
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff8148adf0-ffffffff8148aec7: try_to_unlazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c1500)
Location: fs/namei.c:771
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff814c1500-ffffffff814c15d7: try_to_unlazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool try_to_unlazy(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f39c0)
Location: fs/namei.c:774
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:lookup_fast
  - fs/namei.c:complete_walk
```
**Symbols:**

```
ffffffff814f39c0-ffffffff814f3a97: try_to_unlazy (STB_LOCAL)
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
