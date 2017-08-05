# Snapshot report for `test/templates/p-component.js`

The actual snapshot is saved in `p-component.js.snap`.

Generated by [AVA](https://ava.li).

## isStateless: false, hasStyle: false

> Snapshot 1

    `import React from 'react';␊
    ␊
    class test extends React.Component {␊
      constructor() {␊
        super();␊
        this.state = {};␊
      }␊
    ␊
      render() {␊
        return (␊
          <div>␊
          </div>␊
        );␊
      }␊
    }␊
    ␊
    export default test;␊
    `

> Snapshot 2

    `export default from './test';␊
    `

## isStateless: true, hasStyle: true

> Snapshot 1

    `import React from 'react';␊
    import styles from './style.css';␊
    ␊
    const test = (props) => (␊
      <div className={styles.container}>␊
      </div>␊
    );␊
    ␊
    export default test;␊
    `

> Snapshot 2

    `export default from './test';␊
    `

> Snapshot 3

    `.container {␊
    ␊
    }␊
    `