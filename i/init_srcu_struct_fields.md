# Function: <code>init_srcu_struct_fields</code>

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
In kernel/rcu/srcu.c (ffffffff810e39d6)
Location: kernel/rcu/srcu.c:99
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:init_srcu_struct
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
In kernel/rcu/srcu.c (ffffffff810e9ce6)
Location: kernel/rcu/srcu.c:99
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:init_srcu_struct
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
In kernel/rcu/srcu.c (ffffffff810f0bb6)
Location: kernel/rcu/srcu.c:99
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:init_srcu_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *sp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0f70)
Location: kernel/rcu/srcutree.c:145
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct
```
**Symbols:**

```
ffffffff810f0f70-ffffffff810f1426: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *sp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fad10)
Location: kernel/rcu/srcutree.c:146
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct
```
**Symbols:**

```
ffffffff810fad10-ffffffff810fb186: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *sp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811031c0)
Location: kernel/rcu/srcutree.c:173
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct
```
**Symbols:**

```
ffffffff811031c0-ffffffff8110361e: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110eb70)
Location: kernel/rcu/srcutree.c:179
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct
```
**Symbols:**

```
ffffffff8110eb70-ffffffff8110efce: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118200)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffff81118200-ffffffff811186da: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811245d0)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffff811245d0-ffffffff81124aaa: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811320d0)
Location: kernel/rcu/srcutree.c:181
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
```
**Symbols:**

```
ffffffff811320d0-ffffffff81132205: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d8a0)
Location: kernel/rcu/srcutree.c:168
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
```
**Symbols:**

```
ffffffff8112d8a0-ffffffff8112d9dd: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112ded0)
Location: kernel/rcu/srcutree.c:171
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
```
**Symbols:**

```
ffffffff8112ded0-ffffffff8112e00d: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f380)
Location: kernel/rcu/srcutree.c:163
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
```
**Symbols:**

```
ffffffff8114f380-ffffffff8114f4b9: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:237
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
```
**Symbols:**

```
ffffffff81176510-ffffffff811767bf: init_srcu_struct_fields (STB_LOCAL)
ffffffff81e5e8e7-ffffffff81e5e8fb: init_srcu_struct_fields.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:237
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
```
**Symbols:**

```
ffffffff811adf20-ffffffff811ae1d6: init_srcu_struct_fields (STB_LOCAL)
ffffffff82059f07-ffffffff82059f1b: init_srcu_struct_fields.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:237
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct
```
**Symbols:**

```
ffffffff811bff40-ffffffff811c028f: init_srcu_struct_fields (STB_LOCAL)
ffffffff820d8713-ffffffff820d8727: init_srcu_struct_fields.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d03b0)
Location: kernel/rcu/srcutree.c:237
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct
```
**Symbols:**

```
ffffffff811d03b0-ffffffff811d072f: init_srcu_struct_fields (STB_LOCAL)
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
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800010189b70)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffff800010189b70-ffff800010189f88: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d860c)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
c03d860c-c03d8a38: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e4290)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
c0000000001e4290-c0000000001e48d0: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011ed6a)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffe00011ed6a-ffffffe00011f110: init_srcu_struct_fields (STB_LOCAL)
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
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111cbb0)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffff8111cbb0-ffffffff8111d08a: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110dc70)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffff8110dc70-ffffffff8110e14a: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111aaa0)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffff8111aaa0-ffffffff8111af7a: init_srcu_struct_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_srcu_struct_fields(struct srcu_struct *ssp, bool is_static);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126380)
Location: kernel/rcu/srcutree.c:168
Inline: False
```
**Symbols:**

```
ffffffff81126380-ffffffff8112685a: init_srcu_struct_fields (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
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
