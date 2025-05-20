# Function: <code>rcu_init_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81f7f22d)
Location: kernel/rcu/tree.c:4388
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81f7f22d-ffffffff81f7f602: rcu_init_one.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_init_one(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81fa8298)
Location: kernel/rcu/tree.c:4006
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81fa8298-ffffffff81fa86c8: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_init_one(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81fe40fb)
Location: kernel/rcu/tree.c:4032
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81fe40fb-ffffffff81fe4538: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_init_one(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff820c4cda)
Location: kernel/rcu/tree.c:4031
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff820c4cda-ffffffff820c5104: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_init_one(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff826cd3a8)
Location: kernel/rcu/tree.c:4096
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff826cd3a8-ffffffff826cd7bd: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_init_one(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff826f7572)
Location: kernel/rcu/tree.c:3894
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff826f7572-ffffffff826f7927: rcu_init_one (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff828ae7be)
Location: kernel/rcu/tree.c:3593
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828c7292)
Location: kernel/rcu/tree.c:3274
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828cf888)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82cf0be6)
Location: kernel/rcu/tree.c:4064
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff82cf0be6-ffffffff82cf0f14: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82fdd5c2)
Location: kernel/rcu/tree.c:4385
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff82fdd5c2-ffffffff82fdd8f9: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff831e7e62)
Location: kernel/rcu/tree.c:4501
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff831e7e62-ffffffff831e822e: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff832cbfb0)
Location: kernel/rcu/tree.c:4472
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff832cbfb0-ffffffff832cc586: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8347f95c)
Location: kernel/rcu/tree.c:4638
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8347f95c-ffffffff8347ff66: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff83eac0b0)
Location: kernel/rcu/tree.c:4543
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff83eac0b0-ffffffff83eac9fd: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff836d12d0)
Location: kernel/rcu/tree.c:4703
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff836d12d0-ffffffff836d1c3f: rcu_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_init_one();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff83902960)
Location: kernel/rcu/tree.c:4858
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff83902960-ffffffff839033a8: rcu_init_one (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff800011447058)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (c1521700)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (c00000000136c17c)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffe000008ab2)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828b8580)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828b08b6)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828cb4bc)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828d08b6)
Location: kernel/rcu/tree.c:3338
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
