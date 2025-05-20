# Function: <code>get_raw_hash</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
char *get_raw_hash(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff812ee430)
Location: certs/blacklist.c:146
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
**Symbols:**

```
ffffffff812ee430-ffffffff812ee4e8: get_raw_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *get_raw_hash(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff813589a0)
Location: certs/blacklist.c:146
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
**Symbols:**

```
ffffffff813589a0-ffffffff81358a58: get_raw_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *get_raw_hash(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8138a2f0)
Location: certs/blacklist.c:146
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
**Symbols:**

```
ffffffff8138a2f0-ffffffff8138a3c5: get_raw_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *get_raw_hash(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff813b3e10)
Location: certs/blacklist.c:146
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
**Symbols:**

```
ffffffff813b3e10-ffffffff813b3ee5: get_raw_hash (STB_LOCAL)
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
