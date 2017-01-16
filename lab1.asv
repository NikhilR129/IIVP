%way to declare multi-line comments below
%{
dir
mkdir SampleFolder%dir
help mean
syms a b
f=a+b
%}
clear f; %remove variable from global namespace
exist f; %check if variable is defined in workspace

im = imread('Jellyfish.jpg');
im1=rgb2gray(im);
im2=im2uint16(im1);
subplot(3,2,1);
imshow(im2);
title('uint16');

im3=im2uint8(im1);
subplot(3,2,2);
imshow(im3);
title('uint8');

im4=im2double(im1);
subplot(3,2,3);
imshow(im4);
title('double');

im5=im2single(im1);
subplot(3,2,4);
imshow(im5);
title('single');


%imwrite(im,'jellyfish.png');


%{
    A=[1,2,3,4,5];
disp(A(1:end));


a=[1 2 3; 4 5 6; 7 8 9];
disp(a);
%}

%{
disp(a(1:end,1:end));

disp('Hello World');

save('workspace variables');

load('workspace variables');
%}

%control statements
%if-elseif-else

%{
a=randi(100,1);
if rem(a,2)==0
    disp('a is even');
else
    disp('a is odd');
end
%}

%for loop

%{
for m = 1:5
    for n = 1:5
       disp(m+n)
    end
end
%}

%while loop
m=10;
while m < 10
    disp(m);
    m=m-1;
end










