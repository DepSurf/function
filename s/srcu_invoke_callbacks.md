# Function: <code>srcu_invoke_callbacks</code>

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
In kernel/rcu/srcu.c (ffffffff810e3f3c)
Location: kernel/rcu/srcu.c:618
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
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
In kernel/rcu/srcu.c (ffffffff810ea23b)
Location: kernel/rcu/srcu.c:618
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
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
In kernel/rcu/srcu.c (ffffffff810f111b)
Location: kernel/rcu/srcu.c:618
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f17e0)
Location: kernel/rcu/srcutree.c:1132
Inline: False
```
**Symbols:**

```
ffffffff810f17e0-ffffffff810f195f: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb540)
Location: kernel/rcu/srcutree.c:1133
Inline: False
```
**Symbols:**

```
ffffffff810fb540-ffffffff810fb6c5: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811039c0)
Location: kernel/rcu/srcutree.c:1163
Inline: False
```
**Symbols:**

```
ffffffff811039c0-ffffffff81103b44: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110f380)
Location: kernel/rcu/srcutree.c:1181
Inline: False
```
**Symbols:**

```
ffffffff8110f380-ffffffff8110f504: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811190f0)
Location: kernel/rcu/srcutree.c:1156
Inline: False
```
**Symbols:**

```
ffffffff811190f0-ffffffff81119254: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811254c0)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffffffff811254c0-ffffffff81125624: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81133060)
Location: kernel/rcu/srcutree.c:1172
Inline: False
```
**Symbols:**

```
ffffffff81133060-ffffffff811331d2: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e840)
Location: kernel/rcu/srcutree.c:1161
Inline: False
```
**Symbols:**

```
ffffffff8112e840-ffffffff8112e9b2: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112eac0)
Location: kernel/rcu/srcutree.c:1246
Inline: False
```
**Symbols:**

```
ffffffff8112eac0-ffffffff8112ec47: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1241
Inline: False
```
**Symbols:**

```
ffffffff8114ffa0-ffffffff81150135: srcu_invoke_callbacks (STB_LOCAL)
ffffffff81cae2c2-ffffffff81cae2d7: srcu_invoke_callbacks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1536
Inline: False
```
**Symbols:**

```
ffffffff81177440-ffffffff811775d7: srcu_invoke_callbacks (STB_LOCAL)
ffffffff81e5e90f-ffffffff81e5e924: srcu_invoke_callbacks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1605
Inline: False
```
**Symbols:**

```
ffffffff811aea70-ffffffff811aec07: srcu_invoke_callbacks (STB_LOCAL)
ffffffff82059f1b-ffffffff82059f30: srcu_invoke_callbacks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1681
Inline: False
```
**Symbols:**

```
ffffffff811c0a70-ffffffff811c0c09: srcu_invoke_callbacks (STB_LOCAL)
ffffffff820d8727-ffffffff820d873c: srcu_invoke_callbacks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1701
Inline: False
```
**Symbols:**

```
ffffffff811d0f50-ffffffff811d1115: srcu_invoke_callbacks (STB_LOCAL)
ffffffff821b39dd-ffffffff821b39f2: srcu_invoke_callbacks.cold (STB_LOCAL)
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
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018a768)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffff80001018a768-ffff80001018a9a4: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d81ec)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
c03d81ec-c03d8394: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e57f0)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
c0000000001e57f0-c0000000001e5a98: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011fb10)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffffffe00011fb10-ffffffe00011fcee: srcu_invoke_callbacks (STB_LOCAL)
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
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111daa0)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffffffff8111daa0-ffffffff8111dc04: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110eb40)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffffffff8110eb40-ffffffff8110ec92: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b990)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffffffff8111b990-ffffffff8111baf4: srcu_invoke_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125ef0)
Location: kernel/rcu/srcutree.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81125ef0-ffffffff8112603b: srcu_invoke_callbacks (STB_LOCAL)
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
