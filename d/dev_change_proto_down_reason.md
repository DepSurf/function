# Function: <code>dev_change_proto_down_reason</code>

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
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffc00)
Location: net/core/dev.c:9003
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff819ffc00-ffffffff819ffc9e: dev_change_proto_down_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e7ad0)
Location: net/core/dev.c:9262
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff819e7ad0-ffffffff819e7b68: dev_change_proto_down_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9252
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81d35f2e-ffffffff81d35f85: dev_change_proto_down_reason.cold (STB_LOCAL)
ffffffff81a98ec0-ffffffff81a98f7c: dev_change_proto_down_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8991
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81f02f0f-ffffffff81f02f66: dev_change_proto_down_reason.cold (STB_LOCAL)
ffffffff81c1df90-ffffffff81c1e061: dev_change_proto_down_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8978
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff820ab798-ffffffff820ab812: dev_change_proto_down_reason.cold (STB_LOCAL)
ffffffff81dcf390-ffffffff81dcf486: dev_change_proto_down_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8986
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8212cf14-ffffffff8212cf4c: dev_change_proto_down_reason.cold (STB_LOCAL)
ffffffff81e3ffc0-ffffffff81e4009b: dev_change_proto_down_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dev_change_proto_down_reason(struct net_device *dev, long unsigned int mask, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9104
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8220ec64-ffffffff8220ec9c: dev_change_proto_down_reason.cold (STB_LOCAL)
ffffffff81efe920-ffffffff81efe9fb: dev_change_proto_down_reason (STB_GLOBAL)
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
