# Function: <code>assoc_array_iterate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81405210)
Location: lib/assoc_array.c:145
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_read
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_gc
```
**Symbols:**

```
ffffffff81405210-ffffffff8140522e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8144cdc0)
Location: lib/assoc_array.c:145
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8144cdc0-ffffffff8144cdde: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8146b780)
Location: lib/assoc_array.c:145
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8146b780-ffffffff8146b79e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81470ea0)
Location: lib/assoc_array.c:145
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff81470ea0-ffffffff81470ebe: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8149d660)
Location: lib/assoc_array.c:145
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8149d660-ffffffff8149d67e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff814d2f60)
Location: lib/assoc_array.c:137
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff814d2f60-ffffffff814d2f7e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff814e78c0)
Location: lib/assoc_array.c:137
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff814e78c0-ffffffff814e78de: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81514230)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff81514230-ffffffff8151424e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81534c70)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff81534c70-ffffffff81534c8e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81599390)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff81599390-ffffffff815993ae: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815b4d90)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff815b4d90-ffffffff815b4dae: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815bfbb0)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff815bfbb0-ffffffff815bfbce: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81627510)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff81627510-ffffffff8162752e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff816f8040)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff816f8040-ffffffff816f8076: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff817ea850)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff817ea850-ffffffff817ea886: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8182a9d0)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8182a9d0-ffffffff8182aa06: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8187c470)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8187c470-ffffffff8187c4a6: assoc_array_iterate (STB_GLOBAL)
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
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffff800010641548)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffff800010641548-ffff800010641578: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (c07e6f74)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
c07e6f74-c07e6fa0: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (c0000000007ebe80)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
c0000000007ebe80-c0000000007ebeb8: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffe00046db4e)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffe00046db4e-ffffffe00046db74: assoc_array_iterate (STB_GLOBAL)
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
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8152d250)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8152d250-ffffffff8152d26e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8151d530)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff8151d530-ffffffff8151d54e: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815292e0)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff815292e0-ffffffff815292fe: assoc_array_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int assoc_array_iterate(const struct assoc_array *array, int (*iterator)(const void *, void *), void *iterator_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81542cc0)
Location: lib/assoc_array.c:133
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_gc
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_read
```
**Symbols:**

```
ffffffff81542cc0-ffffffff81542cde: assoc_array_iterate (STB_GLOBAL)
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
