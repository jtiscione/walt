# Snapshot report for `src/generator/__tests__/array-subscript-spec.js`

The actual snapshot is saved in `array-subscript-spec.js.snap`.

Generated by [AVA](https://ava.li).

## generated array offsets

> Snapshot 1

    [
      {
        kind: {
          code: 32,
          first: null,
          name: 'GetLocal',
          result: null,
          second: null,
          size: 0,
          text: 'get_local',
        },
        params: [
          0,
        ],
      },
      {
        kind: {
          code: 65,
          first: null,
          name: 'i32Const',
          result: 1,
          second: null,
          size: 0,
          text: 'i32.const',
        },
        params: [
          1,
        ],
      },
      {
        kind: {
          code: 65,
          first: null,
          name: 'i32Const',
          result: 1,
          second: null,
          size: 0,
          text: 'i32.const',
        },
        params: [
          4,
        ],
      },
      {
        kind: {
          code: 108,
          first: 1,
          name: 'i32Mul',
          result: 1,
          second: 1,
          size: 0,
          text: 'i32.mul',
        },
        params: [],
      },
      {
        kind: {
          code: 106,
          first: 1,
          name: 'i32Add',
          result: 1,
          second: 1,
          size: 0,
          text: 'i32.add',
        },
        params: [],
      },
      {
        kind: {
          code: 40,
          first: 1,
          name: 'i32Load',
          result: 1,
          second: null,
          size: 4,
          text: 'i32.load',
        },
        params: [
          2,
          0,
        ],
      },
    ]

## generates correct offsets for user-defined objects

> Snapshot 1

    [
      {
        kind: {
          code: 32,
          first: null,
          name: 'GetLocal',
          result: null,
          second: null,
          size: 0,
          text: 'get_local',
        },
        params: [
          0,
        ],
      },
      {
        kind: {
          code: 65,
          first: null,
          name: 'i32Const',
          result: 1,
          second: null,
          size: 0,
          text: 'i32.const',
        },
        params: [
          4,
        ],
      },
      {
        kind: {
          code: 106,
          first: 1,
          name: 'i32Add',
          result: 1,
          second: 1,
          size: 0,
          text: 'i32.add',
        },
        params: [],
      },
      {
        kind: {
          code: 40,
          first: 1,
          name: 'i32Load',
          result: 1,
          second: null,
          size: 4,
          text: 'i32.load',
        },
        params: [
          2,
          0,
        ],
      },
    ]