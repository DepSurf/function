# Function: <code>flow_cache_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flow_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff81735160)
Location: net/core/flow.c:340
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_flush_task
  - net/xfrm/xfrm_policy.c:xfrm_dev_event
```
**Symbols:**

```
ffffffff81735160-ffffffff81735322: flow_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flow_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817a12f0)
Location: net/core/flow.c:351
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_flush_task
  - net/xfrm/xfrm_policy.c:xfrm_dev_event
```
**Symbols:**

```
ffffffff817a12f0-ffffffff817a1498: flow_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flow_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817cfbe0)
Location: net/core/flow.c:349
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_flush_task
  - net/xfrm/xfrm_policy.c:xfrm_dev_event
```
**Symbols:**

```
ffffffff817cfbe0-ffffffff817cfdb5: flow_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flow_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817eefe0)
Location: net/core/flow.c:352
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_flush_task
  - net/xfrm/xfrm_policy.c:xfrm_garbage_collect
```
**Symbols:**

```
ffffffff817eefe0-ffffffff817ef1b1: flow_cache_flush (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
