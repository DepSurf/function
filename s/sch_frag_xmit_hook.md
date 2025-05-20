# Function: <code>sch_frag_xmit_hook</code>

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
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81a6fa50)
Location: net/sched/sch_frag.c:138
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_dev_queue_xmit
```
**Symbols:**

```
ffffffff81a6fa50-ffffffff81a6fa92: sch_frag_xmit_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81a58340)
Location: net/sched/sch_frag.c:138
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_dev_queue_xmit
```
**Symbols:**

```
ffffffff81a58340-ffffffff81a58382: sch_frag_xmit_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81b11320)
Location: net/sched/sch_frag.c:139
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_dev_queue_xmit
```
**Symbols:**

```
ffffffff81b11320-ffffffff81b11362: sch_frag_xmit_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81c98400)
Location: net/sched/sch_frag.c:140
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_dev_queue_xmit
```
**Symbols:**

```
ffffffff81c98400-ffffffff81c9845a: sch_frag_xmit_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81e54410)
Location: net/sched/sch_frag.c:140
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_dev_queue_xmit
```
**Symbols:**

```
ffffffff81e54410-ffffffff81e5446a: sch_frag_xmit_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81eafcb0)
Location: net/sched/sch_frag.c:140
Inline: False
```
**Symbols:**

```
ffffffff81eafcb0-ffffffff81eafd0a: sch_frag_xmit_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sch_frag_xmit_hook(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81f72720)
Location: net/sched/sch_frag.c:140
Inline: False
```
**Symbols:**

```
ffffffff81f72720-ffffffff81f7277a: sch_frag_xmit_hook (STB_GLOBAL)
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
