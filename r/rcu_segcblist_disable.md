# Function: <code>rcu_segcblist_disable</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7020)
Location: kernel/rcu/rcu_segcblist.c:97
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
```
**Symbols:**

```
ffffffff810f7020-ffffffff810f7069: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101030)
Location: kernel/rcu/rcu_segcblist.c:80
Inline: False
```
**Symbols:**

```
ffffffff81101030-ffffffff81101079: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811094c0)
Location: kernel/rcu/rcu_segcblist.c:80
Inline: False
```
**Symbols:**

```
ffffffff811094c0-ffffffff811094f5: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81114c90)
Location: kernel/rcu/rcu_segcblist.c:80
Inline: False
```
**Symbols:**

```
ffffffff81114c90-ffffffff81114cc5: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111eab0)
Location: kernel/rcu/rcu_segcblist.c:67
Inline: False
```
**Symbols:**

```
ffffffff8111eab0-ffffffff8111eaf9: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b110)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8112b110-ffffffff8112b153: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811396c0)
Location: kernel/rcu/rcu_segcblist.c:162
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811396c0-ffffffff811396f3: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134190)
Location: kernel/rcu/rcu_segcblist.c:162
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81134190-ffffffff811341c3: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134f70)
Location: kernel/rcu/rcu_segcblist.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81134f70-ffffffff81134fa3: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157770)
Location: kernel/rcu/rcu_segcblist.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81157770-ffffffff811577a3: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811809d0)
Location: kernel/rcu/rcu_segcblist.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811809d0-ffffffff81180a1f: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb240)
Location: kernel/rcu/rcu_segcblist.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811bb240-ffffffff811bb28f: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdbe0)
Location: kernel/rcu/rcu_segcblist.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811cdbe0-ffffffff811cdc2f: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2800)
Location: kernel/rcu/rcu_segcblist.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811e2800-ffffffff811e284f: rcu_segcblist_disable (STB_GLOBAL)
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
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193128)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffff800010193128-ffff800010193198: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0484)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
c03e0484-c03e0568: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee210)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
c0000000001ee210-c0000000001ee280: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe0001257c0)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
```
**Symbols:**

```
ffffffe0001257c0-ffffffe00012580c: rcu_segcblist_disable (STB_GLOBAL)
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
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811236f0)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811236f0-ffffffff81123733: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811161b0)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811161b0-ffffffff811161f3: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811215e0)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811215e0-ffffffff81121623: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_segcblist_disable(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dbf0)
Location: kernel/rcu/rcu_segcblist.c:172
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8112dbf0-ffffffff8112dc33: rcu_segcblist_disable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
