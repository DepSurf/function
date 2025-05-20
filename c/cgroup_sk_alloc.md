# Function: <code>cgroup_sk_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121740)
Location: kernel/cgroup.c:6289
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81121740-ffffffff81121800: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129cc0)
Location: kernel/cgroup.c:6318
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81129cc0-ffffffff81129d98: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128a80)
Location: kernel/cgroup/cgroup.c:5138
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81128a80-ffffffff81128b72: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811350d0)
Location: kernel/cgroup/cgroup.c:5805
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff811350d0-ffffffff811351a4: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81143800)
Location: kernel/cgroup/cgroup.c:5843
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81143800-ffffffff811438cb: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f320)
Location: kernel/cgroup/cgroup.c:5946
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8114f320-ffffffff8114f3d5: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b160)
Location: kernel/cgroup/cgroup.c:6365
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8115b160-ffffffff8115b26c: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166e10)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81166e10-ffffffff81166f2a: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81178500)
Location: kernel/cgroup/cgroup.c:6440
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81178500-ffffffff811785af: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175240)
Location: kernel/cgroup/cgroup.c:6432
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81175240-ffffffff8117533f: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175da0)
Location: kernel/cgroup/cgroup.c:6410
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81175da0-ffffffff81175eb1: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d370)
Location: kernel/cgroup/cgroup.c:6637
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8119d370-ffffffff8119d4b5: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd6c0)
Location: kernel/cgroup/cgroup.c:6671
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff811cd6c0-ffffffff811cd7d5: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210d50)
Location: kernel/cgroup/cgroup.c:6938
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81210d50-ffffffff81210e65: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81226740)
Location: kernel/cgroup/cgroup.c:6919
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff81226740-ffffffff81226855: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e3d0)
Location: kernel/cgroup/cgroup.c:6960
Inline: False
Direct callers:
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8123e3d0-ffffffff8123e4e5: cgroup_sk_alloc (STB_GLOBAL)
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
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8c88)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffff8000101d8c88-ffff8000101d8e28: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b9bc)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
c041b9bc-c041bc58: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000246040)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
c000000000246040-c0000000002462b0: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151bf8)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffe000151bf8-ffffffe000151da6: cgroup_sk_alloc (STB_GLOBAL)
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
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f430)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8115f430-ffffffff8115f54a: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811526c0)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff811526c0-ffffffff811527da: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d200)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8115d200-ffffffff8115d31a: cgroup_sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_sk_alloc(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a350)
Location: kernel/cgroup/cgroup.c:6380
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
**Symbols:**

```
ffffffff8116a350-ffffffff8116a513: cgroup_sk_alloc (STB_GLOBAL)
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
