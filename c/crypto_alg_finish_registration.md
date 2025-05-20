# Function: <code>crypto_alg_finish_registration</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_alg_finish_registration(struct crypto_alg *alg, bool fulfill_requests, struct list_head *algs_to_put);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81705dd0)
Location: crypto/algapi.c:225
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
```
**Symbols:**

```
ffffffff81705dd0-ffffffff81705f0f: crypto_alg_finish_registration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_alg_finish_registration(struct crypto_alg *alg, bool fulfill_requests, struct list_head *algs_to_put);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff817402d0)
Location: crypto/algapi.c:237
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
```
**Symbols:**

```
ffffffff817402d0-ffffffff81740420: crypto_alg_finish_registration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_alg_finish_registration(struct crypto_alg *alg, bool fulfill_requests, struct list_head *algs_to_put);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81781150)
Location: crypto/algapi.c:237
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
```
**Symbols:**

```
ffffffff81781150-ffffffff817812a0: crypto_alg_finish_registration (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
