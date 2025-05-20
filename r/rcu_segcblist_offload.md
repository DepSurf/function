# Function: <code>rcu_segcblist_offload</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b160)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
ffffffff8112b160-ffffffff8112b16f: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139700)
Location: kernel/rcu/rcu_segcblist.c:173
Inline: False
```
**Symbols:**

```
ffffffff81139700-ffffffff8113970f: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811341d0)
Location: kernel/rcu/rcu_segcblist.c:173
Inline: False
```
**Symbols:**

```
ffffffff811341d0-ffffffff811341df: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp, bool offload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134fb0)
Location: kernel/rcu/rcu_segcblist.c:266
Inline: False
```
**Symbols:**

```
ffffffff81134fb0-ffffffff81134fd3: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp, bool offload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811577b0)
Location: kernel/rcu/rcu_segcblist.c:266
Inline: False
```
**Symbols:**

```
ffffffff811577b0-ffffffff811577d3: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp, bool offload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180a20)
Location: kernel/rcu/rcu_segcblist.c:266
Inline: False
```
**Symbols:**

```
ffffffff81180a20-ffffffff81180a56: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp, bool offload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb2a0)
Location: kernel/rcu/rcu_segcblist.c:266
Inline: False
```
**Symbols:**

```
ffffffff811bb2a0-ffffffff811bb2d6: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp, bool offload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdc40)
Location: kernel/rcu/rcu_segcblist.c:266
Inline: False
```
**Symbols:**

```
ffffffff811cdc40-ffffffff811cdc76: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp, bool offload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2860)
Location: kernel/rcu/rcu_segcblist.c:266
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:rdp_offload_toggle
```
**Symbols:**

```
ffffffff811e2860-ffffffff811e2896: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193198)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
ffff800010193198-ffff8000101931c4: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0568)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
c03e0568-c03e0588: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee280)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
c0000000001ee280-c0000000001ee294: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe00012580c)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
ffffffe00012580c-ffffffe000125832: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123740)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
ffffffff81123740-ffffffff8112374f: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116200)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
**Symbols:**

```
ffffffff81116200-ffffffff8111620f: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121630)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
ffffffff81121630-ffffffff8112163f: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_segcblist_offload(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dc40)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
```
**Symbols:**

```
ffffffff8112dc40-ffffffff8112dc4f: rcu_segcblist_offload (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool offload</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
