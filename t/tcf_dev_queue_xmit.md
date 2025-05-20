# Function: <code>tcf_dev_queue_xmit</code>

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
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7aea0)
Location: net/sched/act_api.c:30
Inline: False
```
**Symbols:**

```
ffffffff81a7aea0-ffffffff81a7aebc: tcf_dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a63c00)
Location: net/sched/act_api.c:30
Inline: False
```
**Symbols:**

```
ffffffff81a63c00-ffffffff81a63c1c: tcf_dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1cf80)
Location: net/sched/act_api.c:30
Inline: False
```
**Symbols:**

```
ffffffff81b1cf80-ffffffff81b1cf99: tcf_dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca4320)
Location: net/sched/act_api.c:32
Inline: False
```
**Symbols:**

```
ffffffff81ca4320-ffffffff81ca4349: tcf_dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e60ca0)
Location: net/sched/act_api.c:33
Inline: False
```
**Symbols:**

```
ffffffff81e60ca0-ffffffff81e60cc9: tcf_dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebd250)
Location: net/sched/act_api.c:33
Inline: True
```
**Symbols:**

```
ffffffff81ebd250-ffffffff81ebd279: tcf_dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_dev_queue_xmit(struct sk_buff *skb, int (*xmit)(struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80440)
Location: net/sched/act_api.c:33
Inline: True
```
**Symbols:**

```
ffffffff81f80440-ffffffff81f80469: tcf_dev_queue_xmit (STB_GLOBAL)
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
