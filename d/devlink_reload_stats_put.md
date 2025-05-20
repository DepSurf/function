# Function: <code>devlink_reload_stats_put</code>

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
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a66a50)
Location: net/core/devlink.c:540
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff81a66a50-ffffffff81a66dda: devlink_reload_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a49c90)
Location: net/core/devlink.c:543
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff81a49c90-ffffffff81a49ffa: devlink_reload_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b01bf0)
Location: net/core/devlink.c:640
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff81b01bf0-ffffffff81b01fa5: devlink_reload_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85760)
Location: net/core/devlink.c:857
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff81c85760-ffffffff81c85b26: devlink_reload_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3fa50)
Location: net/core/devlink.c:1033
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff81e3fa50-ffffffff81e3fe12: devlink_reload_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82042fa0)
Location: net/devlink/dev.c:78
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff82042fa0-ffffffff82043377: devlink_reload_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_reload_stats_put(struct sk_buff *msg, struct devlink *devlink, bool is_remote);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff821023f0)
Location: net/devlink/dev.c:79
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
```
**Symbols:**

```
ffffffff821023f0-ffffffff821027c7: devlink_reload_stats_put (STB_LOCAL)
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
