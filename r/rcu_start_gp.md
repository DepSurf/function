# Function: <code>rcu_start_gp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool rcu_start_gp(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e6140)
Location: kernel/rcu/tree.c:2201
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810e6140-ffffffff810e61b0: rcu_start_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool rcu_start_gp(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb6b0)
Location: kernel/rcu/tree.c:2313
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810eb6b0-ffffffff810eb720: rcu_start_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rcu_start_gp(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f3340)
Location: kernel/rcu/tree.c:2317
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810f3340-ffffffff810f33b0: rcu_start_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rcu_start_gp(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4430)
Location: kernel/rcu/tree.c:2342
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810f4430-ffffffff810f44bf: rcu_start_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rcu_start_gp(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fd920)
Location: kernel/rcu/tree.c:2414
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810fd920-ffffffff810fd9af: rcu_start_gp (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
