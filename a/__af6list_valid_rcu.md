# Function: <code>__af6list_valid_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c7b2)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d8e1)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180eab6)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187efbf)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fd79)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81881136)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b386f)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4629)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b59e6)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818da225)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818dafcd)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc315)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195fe15)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960bad)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961f05)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b95c2)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba378)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb6c6)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f0892)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1cc8)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2946)
Location: net/netlabel/netlabel_addrlist.h:151
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5fb34)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a606c4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61c7b)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a96764)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a972f4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9885b)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91df4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93511)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93f7b)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1aed)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba3165)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3be0)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90bcd)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92285)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92d00)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5d36d)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5ea25)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f4a0)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dff2f5)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00c58)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01879)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd3fb5)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5aa8)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6709)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204fc05)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205175f)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820523c9)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff821222b5)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123f2f)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124bb9)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffff800010d65948)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66ac0)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68024)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c0e642dc)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (c0e651b8)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66794)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c000000000ea1964)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2dd8)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4a20)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffe0008995da)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a418)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b452)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a35af4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36684)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37beb)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f2714)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f32a4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f480b)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa19a4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2534)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3a9b)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aadcf2)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae8a4)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafec0)
Location: net/netlabel/netlabel_addrlist.h:137
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
</ul>

## Differences
