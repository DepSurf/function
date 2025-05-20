# Function: <code>avc_node_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void avc_node_delete(struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81340210)
Location: security/selinux/avc.c:493
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff81340210-ffffffff81340254: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void avc_node_delete(struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813758b0)
Location: security/selinux/avc.c:493
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff813758b0-ffffffff813758f4: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void avc_node_delete(struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138c1e0)
Location: security/selinux/avc.c:493
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff8138c1e0-ffffffff8138c224: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void avc_node_delete(struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a1f30)
Location: security/selinux/avc.c:493
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff813a1f30-ffffffff813a1f74: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void avc_node_delete(struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c7d30)
Location: security/selinux/avc.c:489
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff813c7d30-ffffffff813c7d74: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f7380)
Location: security/selinux/avc.c:510
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff813f7380-ffffffff813f73c9: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81412e30)
Location: security/selinux/avc.c:510
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff81412e30-ffffffff81412e79: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814408c0)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff814408c0-ffffffff81440909: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145a190)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff8145a190-ffffffff8145a1d9: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814adac6)
Location: security/selinux/avc.c:438
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cb546)
Location: security/selinux/avc.c:441
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d1b76)
Location: security/selinux/avc.c:442
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8152a907)
Location: security/selinux/avc.c:442
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815c02d0)
Location: security/selinux/avc.c:442
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166c810)
Location: security/selinux/avc.c:442
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a58a2)
Location: security/selinux/avc.c:439
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_ss_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e22e2)
Location: security/selinux/avc.c:439
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_ss_reset
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
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff800010546908)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffff800010546908-ffff80001054698c: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fc2ec)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
c06fc2ec-c06fc354: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069d110)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
c00000000069d110-c00000000069d1a4: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a2040)
Location: security/selinux/avc.c:438
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
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
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81452770)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff81452770-ffffffff814527b9: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814431c0)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff814431c0-ffffffff81443209: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144e810)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff8144e810-ffffffff8144e859: avc_node_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void avc_node_delete(struct selinux_avc *avc, struct avc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81465be0)
Location: security/selinux/avc.c:438
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
**Symbols:**

```
ffffffff81465be0-ffffffff81465c29: avc_node_delete (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_avc *avc</code>
</li>
<li>
<b>Param reordered. </b>
<code>node</code> ➡️ <code>avc, node</code>
</li>
</ul>
</details>
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
