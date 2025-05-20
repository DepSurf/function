# Function: <code>dh_safe_prime_free_instance</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dh_safe_prime_free_instance(struct kpp_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff816540da)
Location: crypto/dh.c:297
Inline: True
Inline callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff81653bc0-ffffffff81653bed: dh_safe_prime_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dh_safe_prime_free_instance(struct kpp_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff8170e050)
Location: crypto/dh.c:297
Inline: True
Inline callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff8170de80-ffffffff8170dead: dh_safe_prime_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dh_safe_prime_free_instance(struct kpp_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff81748786)
Location: crypto/dh.c:297
Inline: True
Inline callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff817485b0-ffffffff817485dd: dh_safe_prime_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dh_safe_prime_free_instance(struct kpp_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff8178a625)
Location: crypto/dh.c:297
Inline: True
Inline callers:
  - crypto/dh.c:__dh_safe_prime_create
```
**Symbols:**

```
ffffffff8178a420-ffffffff8178a44d: dh_safe_prime_free_instance (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
