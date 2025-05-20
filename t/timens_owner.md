# Function: <code>timens_owner</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81159b90)
Location: kernel/time/namespace.c:335
Inline: False
```
**Symbols:**

```
ffffffff81159b90-ffffffff81159b9f: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81155ba0)
Location: kernel/time/namespace.c:324
Inline: False
```
**Symbols:**

```
ffffffff81155ba0-ffffffff81155baf: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81156fd0)
Location: kernel/time/namespace.c:324
Inline: False
```
**Symbols:**

```
ffffffff81156fd0-ffffffff81156fdf: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8117be20)
Location: kernel/time/namespace.c:324
Inline: False
```
**Symbols:**

```
ffffffff8117be20-ffffffff8117be2f: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811b1540)
Location: kernel/time/namespace.c:324
Inline: False
```
**Symbols:**

```
ffffffff811b1540-ffffffff811b1555: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f2250)
Location: kernel/time/namespace.c:342
Inline: False
```
**Symbols:**

```
ffffffff811f2250-ffffffff811f2265: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff812069e0)
Location: kernel/time/namespace.c:342
Inline: False
```
**Symbols:**

```
ffffffff812069e0-ffffffff812069f5: timens_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct user_namespace *timens_owner(struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121dbf0)
Location: kernel/time/namespace.c:342
Inline: False
```
**Symbols:**

```
ffffffff8121dbf0-ffffffff8121dc05: timens_owner (STB_LOCAL)
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
