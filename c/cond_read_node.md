# Function: <code>cond_read_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8135b2fc)
Location: security/selinux/ss/conditional.c:399
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813912ae)
Location: security/selinux/ss/conditional.c:399
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813a7ede)
Location: security/selinux/ss/conditional.c:401
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813be88b)
Location: security/selinux/ss/conditional.c:402
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff813e4a2b)
Location: security/selinux/ss/conditional.c:401
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814156e2)
Location: security/selinux/ss/conditional.c:401
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81431ca2)
Location: security/selinux/ss/conditional.c:401
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8145f711)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814794c1)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cond_read_node(struct policydb *p, struct cond_node *node, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:373
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
**Symbols:**

```
ffffffff814ce6e0-ffffffff814ce7f8: cond_read_node (STB_LOCAL)
ffffffff814cef45-ffffffff814cef71: cond_read_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cond_read_node(struct policydb *p, struct cond_node *node, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/conditional.c (0)
Location: security/selinux/ss/conditional.c:373
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
**Symbols:**

```
ffffffff814ebb20-ffffffff814ebc38: cond_read_node (STB_LOCAL)
ffffffff81bf11cd-ffffffff81bf11f9: cond_read_node.cold (STB_LOCAL)
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
In security/selinux/ss/conditional.c (ffffffff814f2a2c)
Location: security/selinux/ss/conditional.c:373
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
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
In security/selinux/ss/conditional.c (ffffffff8154d43d)
Location: security/selinux/ss/conditional.c:376
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
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
In security/selinux/ss/conditional.c (ffffffff815e6435)
Location: security/selinux/ss/conditional.c:376
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
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
In security/selinux/ss/conditional.c (ffffffff81695a74)
Location: security/selinux/ss/conditional.c:376
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
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
In security/selinux/ss/conditional.c (ffffffff816cdf84)
Location: security/selinux/ss/conditional.c:376
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
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
In security/selinux/ss/conditional.c (ffffffff8170a5a4)
Location: security/selinux/ss/conditional.c:376
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffff80001056993c)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (c071d580)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (c0000000006cce60)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
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
In security/selinux/ss/conditional.c (ffffffe0003be970)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81471aa1)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814624c1)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8146db41)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814853b1)
Location: security/selinux/ss/conditional.c:395
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
