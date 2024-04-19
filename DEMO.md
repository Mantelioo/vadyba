.eslintrc.json
{
  "extends": ["next/core-web-vitals", "prettier"],
  "rules": {"indent":"error"}
}
/ These changes will throw bunch of errors after running "npm run lint"


/__tests__/demo.test.ts
Created a demo test with the following code:

describe("demo_test",()=>{
    test("demo_test1",()=>{
        // expect(1).toStrictEqual(2) / This will throw an error
        expect(1).toStrictEqual(1)
    })
})