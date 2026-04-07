# repo-no-3
merge conflicts

FROM    gcc:latest

WORKDIR   /cdac/ditiss/mycode

COPY    user_input.c    /cdac/ditiss/mycode

RUN    gcc    -o    user_input     user_input.c

CMD ["./user_input"]
<img width="925" height="607" alt="image" src="https://github.com/user-attachments/assets/5c4f9489-9518-450a-ae1d-268f8f97737a" />
