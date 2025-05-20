# Function: <code>mutex_trylock_recursive</code>

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
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff811035d0)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff811035d0-ffffffff8110363a: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110e0f0)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff8110e0f0-ffffffff8110e15a: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110b3b0)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff8110b3b0-ffffffff8110b41a: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010168780)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffff800010168780-ffff800010168830: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4e88)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
c03b4e88-c03b4f38: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c0550)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
c0000000001c0550-c0000000001c05f8: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a4ac)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffe00010a4ac-ffffffe00010a520: mutex_trylock_recursive (STB_GLOBAL)
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
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc8e0)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff810fc8e0-ffffffff810fc94a: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ecaf0)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff810ecaf0-ffffffff810ecb5a: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9aa0)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff810f9aa0-ffffffff810f9b0a: mutex_trylock_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum mutex_trylock_recursive_enum mutex_trylock_recursive(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104c10)
Location: kernel/locking/mutex.c:90
Inline: False
```
**Symbols:**

```
ffffffff81104c10-ffffffff81104c7a: mutex_trylock_recursive (STB_GLOBAL)
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
