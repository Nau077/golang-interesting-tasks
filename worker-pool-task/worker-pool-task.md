Реализовать функцию для параллельного выполнения тасок в n параллельных горутинах:

- количество создаваемых горутин не должно зависеть от числа заданий, т.е. функция должна запусать n горутин для параллельно обработки заданий и, возможно, еще несколько вспомогательных горутин;
- функция должна останавливать свою работу, если произошло m ошибок;
- после завершения работы функции (успешного или из-за превышения m) не должно оставаться работающих горутин;
- если задачи работают без ошибок, то выполнятся len(tasks) задач (т.е. все задачи);
- если в первых m задачах происходят ошибки, то всего выполнится не более n+m задач.
