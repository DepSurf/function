# Function: <code>devlink_linecard_types_init</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_linecard_types_init(struct devlink_linecard *linecard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c75fe0)
Location: net/core/devlink.c:10198
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_linecard_create
```
**Symbols:**

```
ffffffff81c75fe0-ffffffff81c7607d: devlink_linecard_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_linecard_types_init(struct devlink_linecard *linecard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2e740)
Location: net/core/devlink.c:10886
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_linecard_create
```
**Symbols:**

```
ffffffff81e2e740-ffffffff81e2e7dd: devlink_linecard_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_linecard_types_init(struct devlink_linecard *linecard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820308b0)
Location: net/devlink/leftover.c:7454
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_linecard_create
```
**Symbols:**

```
ffffffff820308b0-ffffffff8203094d: devlink_linecard_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_linecard_types_init(struct devlink_linecard *linecard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/linecard.c (ffffffff821197e0)
Location: net/devlink/linecard.c:400
Inline: False
Direct callers:
  - net/devlink/linecard.c:devl_linecard_create
```
**Symbols:**

```
ffffffff821197e0-ffffffff8211987d: devlink_linecard_types_init (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
