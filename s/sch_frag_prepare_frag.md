# Function: <code>sch_frag_prepare_frag</code>

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
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81a6f520)
Location: net/sched/sch_frag.c:48
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81a6f520-ffffffff81a6f5fa: sch_frag_prepare_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81a57df0)
Location: net/sched/sch_frag.c:48
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81a57df0-ffffffff81a57ed0: sch_frag_prepare_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81b10dc0)
Location: net/sched/sch_frag.c:49
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81b10dc0-ffffffff81b10e9f: sch_frag_prepare_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81c97c80)
Location: net/sched/sch_frag.c:50
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81c97c80-ffffffff81c97d57: sch_frag_prepare_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:50
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81e53bb0-ffffffff81e53ce6: sch_frag_prepare_frag (STB_LOCAL)
ffffffff820ad5ce-ffffffff820ad5e3: sch_frag_prepare_frag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:50
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81eaf420-ffffffff81eaf562: sch_frag_prepare_frag (STB_LOCAL)
ffffffff8212e778-ffffffff8212e795: sch_frag_prepare_frag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sch_frag_prepare_frag(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_frag.c (0)
Location: net/sched/sch_frag.c:50
Inline: False
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81f71ea0-ffffffff81f71fe2: sch_frag_prepare_frag (STB_LOCAL)
ffffffff82210516-ffffffff82210533: sch_frag_prepare_frag.cold (STB_LOCAL)
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
