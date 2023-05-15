# LearnJest

https://jestjs.io/docs/getting-started

https://jestjs.io/blog/2018/05/29/jest-23-blazing-fast-delightful-testing#snapshot-property-matchers

https://testing-library.com/docs/queries/about/


JEST code example:
screen.debug(undefined, 9999);\
npm run test -- -u\
--Update all Snapshot\
npm run test:cover -- -u

--Single File Test\
npm test ConfirmNclex

--Full test
.\cover.ps1
.\cover.ps1 -- --RunInBand

--Watch test
npm test --watch
npm test -- --RunInBand

--test before PR
npm test


// Due to the nature of the implementation, it cannot be tested with Jest
/* istanbul ignore next */

// await findByText(/Yes/);
screen.debug(undefined, 99999);

console.dir(result);

console.log(pettyDom(Container))

act(() => {
    jest.advanceTimersByTime(301000);
});


await waitFor(() => {
    expect(container.getElementsByClassName("ant-skeleton").length).toBe(1);
    console.log(prettyDOM(myContainer));
});

How to test onchange:
if (values.hasOwnProperty("<customTesting>")) ==> Submit not testing.


