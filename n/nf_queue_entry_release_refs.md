# Function: <code>nf_queue_entry_release_refs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81752720)
Location: net/netfilter/nf_queue.c:49
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81752720-ffffffff817527af: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff817be840)
Location: net/netfilter/nf_queue.c:47
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff817be840-ffffffff817be8cf: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff817ee110)
Location: net/netfilter/nf_queue.c:47
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff817ee110-ffffffff817ee19f: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8180e220)
Location: net/netfilter/nf_queue.c:47
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff8180e220-ffffffff8180e2af: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8188d730)
Location: net/netfilter/nf_queue.c:47
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff8188d730-ffffffff8188d7c5: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff818e1330)
Location: net/netfilter/nf_queue.c:49
Inline: True
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff818e1330-ffffffff818e13c5: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8190dec0)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff8190dec0-ffffffff8190df79: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff8196f930)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff8196f930-ffffffff8196f9ea: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff819a6410)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff819a6410-ffffffff819a64ca: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a8f620)
Location: net/netfilter/nf_queue.c:49
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81a8f620-ffffffff81a8f6bb: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a99610)
Location: net/netfilter/nf_queue.c:49
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81a99610-ffffffff81a996ab: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81a84920)
Location: net/netfilter/nf_queue.c:49
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81a84920-ffffffff81a849bb: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81b3ef20)
Location: net/netfilter/nf_queue.c:58
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81b3ef20-ffffffff81b3ef8d: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81ccb630)
Location: net/netfilter/nf_queue.c:58
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81ccb630-ffffffff81ccb6a5: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81e8b440)
Location: net/netfilter/nf_queue.c:58
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81e8b440-ffffffff81e8b4b5: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81ee9490)
Location: net/netfilter/nf_queue.c:58
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81ee9490-ffffffff81ee9505: nf_queue_entry_release_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81fad200)
Location: net/netfilter/nf_queue.c:58
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:__nf_queue
```
**Symbols:**

```
ffffffff81fad200-ffffffff81fad275: nf_queue_entry_release_refs (STB_LOCAL)
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
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffff800010c55c40)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffff800010c55c40-ffff800010c55d6c: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (c0d65644)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
c0d65644-c0d65774: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (c000000000d56160)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
c000000000d56160-c000000000d5630c: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffe0007bfe60)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffe0007bfe60-ffffffe0007bff90: nf_queue_entry_release_refs (STB_GLOBAL)
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
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81946280)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff81946280-ffffffff8194633a: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff818ffd70)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff818ffd70-ffffffff818ffe2a: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff81997410)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
**Symbols:**

```
ffffffff81997410-ffffffff819974ca: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nf_queue_entry_release_refs(struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_queue.c (ffffffff819ba0f0)
Location: net/netfilter/nf_queue.c:67
Inline: False
Direct callers:
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_reinject
  - net/netfilter/nf_queue.c:nf_queue
```
**Symbols:**

```
ffffffff819ba0f0-ffffffff819ba1aa: nf_queue_entry_release_refs (STB_GLOBAL)
```
</details>
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
