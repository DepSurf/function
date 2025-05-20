# Function: <code>sch_fragment</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:82
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81a6f600-ffffffff81a6fa4c: sch_fragment (STB_LOCAL)
ffffffff81c320ef-ffffffff81c32153: sch_fragment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:82
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81a57ed0-ffffffff81a5833a: sch_fragment (STB_LOCAL)
ffffffff81c243d0-ffffffff81c24437: sch_fragment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:83
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81b10ea0-ffffffff81b1131c: sch_fragment (STB_LOCAL)
ffffffff81d38de9-ffffffff81d38e50: sch_fragment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:84
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81c97f60-ffffffff81c983fe: sch_fragment (STB_LOCAL)
ffffffff81f05658-ffffffff81f056bd: sch_fragment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81e53f10)
Location: net/sched/sch_frag.c:84
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81e53f10-ffffffff81e543f7: sch_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81eaf790)
Location: net/sched/sch_frag.c:84
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81eaf790-ffffffff81eafc99: sch_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sch_fragment(struct net *net, struct sk_buff *skb, u16 mru, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81f72210)
Location: net/sched/sch_frag.c:84
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
**Symbols:**

```
ffffffff81f72210-ffffffff81f7270a: sch_fragment (STB_LOCAL)
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
