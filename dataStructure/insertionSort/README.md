# ���� ����

���� ������ �� ��Ҹ� �̾Ƴ��� ������ ���� �����ϸ� ������ �ϴ� ����̴�.  
���� �����ϸ� ī�� ���̸� �� �� ī�带 5�� �޾Ҵٰ� ġ��.  
������� ���� 5���� ī�带 �����ϱ� ���� ���徿 �̾� ������ ��ġ�� �ִ´�.  

## ����
1. ���� ���� ����� �Ǵ� ��ҵ��� �����Ѵ�.  
���� ����� ���ʺ��� �����س����µ�, ó���� 2���̸� �ݺ� Ƚ���� ���� �� ���� ���� ����� 1���� Ŀ����.  
���� ���̰� n�� �迭�� ���� ��� �ִ� ������ n-1���̴�.  

2. ���� ����� ���� �����ʿ� �ִ� ��Ұ� ���� ��� �� ���� ū ������ Ȯ���Ѵ�.  
���� �׷��� �ʴٸ� �ش� ��Ҹ� �̾Ƴ��� ���� ��� �� ��ġ�ؾ� �� ������ ���� ã�´�.  
�� ���ʿ� ��ġ�� ��Һ��� ũ��, �����ʿ� ��ġ�� ��Һ��� ���� �� ���̿� ���� �Ѵ�.  

3. ������ ��ġ�� ã�Ҵٸ� �� ã�� ��ġ�� �����ʿ� �ִ� ��ҵ��� ���������� 1ĭ�� �̵���Ų��.  
�̷��� �Ǹ� �� ������ ����µ� �װ��� ���� ��Ҹ� ����ִ´�.  
���� ������ ��ġ�� ���� ��� ���� �������� ã�´�.

4. ��� �����Ͱ� ������ �Ϸ�� �� ���� 1-3���� �ݺ��Ѵ�.  

## �迭�� �����ϱ�
�Ʒ��� ���� ������ �迭�� �ִ�.  
``` int numberArray[] = {4, 2, 1, 3}; ```

**����-1��**�� �ǰ��Ͽ� ���� ����� ���ʺ��� ������ ������ �� ����� 2���̴�.  
����� ���� ���ʿ� �ִ� �� ���� ��� 4�� 2�� �Ǹ� ���� ���ϴ� 2�� �� �۴�.
**����-2��**�� �ǰ��Ͽ� 2�� �̴´�.  
**{4, [], 1, 3}**

���� **����-3��**�� �ǰ��Ͽ� ���� 2�� �� �ڸ��� 4�� ���� �ڸ��̴�.  
�׷��ٸ� 4�� ���������� �� ĭ �̵���Ų��.  
**{[], 4, 1, 3}**

���� �� ������ �������Ƿ� �ش� �ڸ��� 2�� �ִ´�.  
**{2, 4, 1, 3}**

**����-1��**�� �ǰ��Ͽ� ���� ����� �ϳ� �� �ø���.  
2, 4, 1�� ���� ����� �Ǵµ� ���� �����ʿ� 1�� ��ġ�� �ְ� �ٷ� �տ��� 4�� ��ġ�������Ƿ� 1�� �̴´�.  
**{2, 4, [], 3}**

���� ����� ��ȸ�ϸ� ���� ���غ��� 1�� 2�� 4���� �����Ƿ� 2�� �տ� ��ġ�ؾ� �Ѵ�.  
���� 2�� 4�� ���������� �� ĭ �̵���Ų��.  
**{[], 2, 4, 3}**

���� �� ������ 1�� �ִ´�.  
**{1, 2, 4, 3}**

���� ���� ����� �ϳ� �� �ø���.  
��� ��Ұ� ���� ����� �Ǿ��� ���� �����ʿ� �ִ� 3�� �տ� �ִ� 4���� �����Ƿ� 3�� �̴´�.  
**{1, 2, 4, []}**

���� ���غ��� 3�� 4���� �۰� 2���� ũ�Ƿ� 3�� ��ġ�� ���� 4�� ���̴�.  
���� 4�� ���������� �� ĭ �̵���Ų��.  
**{1, 2, [], 4}**

���� �� ������ 3�� ���� �ִ´�.  
**{1, 2, 3, 4}**

## ����
���� ����� ��Ұ� 4����� ��� ������ 2������ �� 1��, 3���� �� 2��, 4���� �� 3���� �񱳸� �����Ѵ�.  
���� n���� �� n-1���� �񱳸� �����ϹǷ� �Ʒ��� ���� ���� ���� �� �ִ�.  
**���� ������ �� Ƚ�� = 1 + 2 + 3 + ... + (n-2) + (n-1) = n(n-1) / 2**

�� �� Ƚ���� ���� ������ �� Ƚ���� ������ �������� �ִ�.  
�츮�� �ߴ� ������ ���� ���� ����� 2���� �� 4�� 2�� �������Ƿ� �� Ƚ���� 1ȸ�̴�.  
���� ����� 3������ �� 1�� 4, 1�� 2�� �������Ƿ� �� Ƚ���� 2ȸ�̴�.  
���� ����� 4������ �� 3�� 4, 3�� 2�� �������Ƿ� �� Ƚ���� 2ȸ�̴�.  

���� �����̿��ٸ� 1 + 2 + 3 = 6ȸ �񱳶�� ������ �������� ���� ���� ���Ŀ����� 1 + 2 + 2 = 5ȸ���̿���.  
���� ���İ� �ٸ��� ���� ������ ������ �̹� �Ǿ��ִٸ� �� ���� �񱳸� ��ģ��.  
���� ���� �������� �Ʒ��� ���� ���ִ� �迭�� ���� ���ķ� �����Ѵٰ� �غ���.  
**{1, 2, 3, 4}**

���� ���� ����� 2���̹Ƿ� 2�� 1�� ���Ѵ�.  
2�� ���� ��󿡼� ���� �����ʿ� ��ġ�ϹǷ� ���� ���μ����� �����Ѵ�.  

���� ���� ����� 3���̴�.  
3�� 2�� ���غ��� 3�� �� ũ�� ���� �����ʿ� ��ġ�ϹǷ� ���� ���μ����� �����Ѵ�.  

���� ��� ��Ұ� ���� ����̴�.  
4�� 3�� ���غ��� 4�� �� ũ�� ���� �����ʿ� ��ġ�ϹǷ� ������ �����Ѵ�.  

4���� ��Ұ� �̹� ���ĵǾ� �ְ� ���� ���� Ƚ���� 1 + 1 + 1 = 3�̴�.  
�׷��ٸ� n���� ��Ұ� ���� ���ķ� ���� �� �ִ� ���� �̻����� �� Ƚ���� �Ʒ��� ����.  
**���� ���� �ּ� �� Ƚ�� = n-1**

�׷� ���� ������ ��� ������ (�ִ� �� Ƚ�� + �ּ� ��Ƚ��) / 2�̹Ƿ� �Ʒ��� ����.  
**���� ���� ��� �� Ƚ�� = (n(n-1) / 2 + n-1) / 2 = (n^2 + n - 2) / 2**

Ȯ���Ѱ� ���� ���ĺ��� ���� ������ �����ش�.  